#Floating point equality

Avoid using operator == and operator != with floating point operands in c++

**Libraries**
algorithm   // std::max
cmath       // std::abs

**Epsilon Value**
The value used to represent "close enough" is traditionally called epsilon

**approximatelyEqualAbsRel Function**
This function receives 4 parameters, the 2 floating point numbers to compare, an absolute epsilon very close to zero (e.g. 1e-12), and a relative epsilon that will serve as a percentage for the Knuth's approach.