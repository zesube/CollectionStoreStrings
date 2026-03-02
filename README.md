### Errors Fixed

#### 
Fixed package name mismatch: stringCollections -> stringsCollections. 

Fixed wrong generic type in count: ArrayList<Integer> -> ArrayList<String>.

Fixed logic error in count (was starting at 1 and overcounting); now returns words.size().

Fixed invalid boolean literals: False/True -> false/true.

Fixed invalid generic declaration: ArrayList<> items -> ArrayList<String> items.

Fixed invalid list declaration in main: ArrayList<> states = new ArrayList<Integer>() -> ArrayList<String> states = new ArrayList<String>().

Added a missing semicolon after states.add("New York").

Added a missing semicolon after System.out.println(state).

Could you make sure all list element types match usage (String states and string loop variable)?
