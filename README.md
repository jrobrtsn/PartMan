# PartMan electronic parts inventory managment software
simple Qt-based electronic component parts database utility

# V1 Goals:
  1. simple structure for viewing all components and adding/removing quantities 
  2. easy (manual) addition of components to stock list 
  3. BoM creation utility for marking integer multiples of components used
    3.1. BoM cost analysis tools



# V2 goals:

  1. scanner support
     1.1.  and large external DB for component reel codes for automatically adding components
     1.2.  automatic parts viewing via scanner to mark used/decrease stock Qty
  2. BoM utilities expanded
     2.1.  Create printable BoMs with desagnators collated by value, footprint, ratings and component type
     2.2.  Unique BoM ID scannable to mark as used upon component use.
  3. Basic component images, e.g. smt_cap.png for a SMT capacitor etc etc...
  4. low quantity warnings when less than 10% of maximum quantity recorded of each component left
  5. Sorting by [field] utility 


# V3 goals:
  1. migration to libadwaita/gtk4 as I prefer that, just cannot be bothered leaning how to write the XML for it
  2


# ------------------------------------------------------------------------------------------------------------------
# building/compiling
open project in Qt Creator and compile or IDK this is just hypothetical right now 
