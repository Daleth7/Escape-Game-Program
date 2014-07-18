1. All class data members will be prefixed with "m_"
2. Class names will start uppercased
3. All class member definitions shall be kept in another file while the class definition shows only member declarations.

```C++
///////////////////////////////////////////////////////
//                       header                      //
///////////////////////////////////////////////////////
#ifndef INCLUDE_GUARD_
#define INCLUDE_GUARD_

class Foobar // (2)
{
    public:
        void funky();

    private:
        int m_baz; // (1)
};

#endif
```


```C++ 
///////////////////////////////////////////////////////
//                     source                        //
///////////////////////////////////////////////////////

#include "header.h"

// (3)
void Foobar::funky()
{
} 
```
