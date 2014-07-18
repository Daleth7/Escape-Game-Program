Physical Objects

* Map
```C++
// For the alpha version, the map shall consist of fixed dimensions: 6x6x6
struct Map{
        //Accessing individual blocks will involve three indices
    const Block& get_block(unit_type, unit_type, unit_type)const;

};
```


* Block
```C++
struct Block{
};

struct Wall : public Block{
};
```


* Entities
```C++
struct  Entity{
    unit_type sanity()const; //All entities shall have sanity levels

    void change_sanity(unit_type);
};

Entity player;
Entity combatant;
```


* Inventory
```C++
struct Inventory{
};
```


* Item
```C++
struct Item{
};
```


* Challenge Database
```C++
struct Challenge_Data{
};

class Challenge{
    public:
        size_type id()const;
        bool complete()const;

    private:
        typedef container_template<Challenge> container_type;

        size_type m_id;
        container_type m_conditions;
};
```


* User Interface
```C++
// As a 3-D program, the graphics of the program will be minimal
//    in the alpha version, i.e. mainly primitive shapes with 2-D texture.
struct UI{
};

struct Block_Sprite{
        //Each sprite will have to know its own position and orientation
        //    for the purposes of rendering.
    unit_type get_x()const;
    unit_type get_y()const;
    unit_type get_z()const;
    unit_type get_alpha()const;
    unit_type get_beta()const;
    unit_type get_gamma()const;
};
```


----------------------------------------------------------------------------------------------
Actions and interactions

* Starting and introducing the player to the game
```C++
void game_intro(){
}
```


* Positioning
```C++
```
 


* Solving
```C++
```
 


* Item consuming
```C++
```


* Combating
```C++
```


* Winning 
```C++
```


* Saving
```C++
```
