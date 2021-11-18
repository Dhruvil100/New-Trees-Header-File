# New-Trees-Header-File
We have made a new custom made header file for Trees Data Structure in C++.
 
Custom Libararies are available for BINARY SEARCH TREE, TREES and AVL.

## Binary Search Tree :

To use this header file copy the below given code in your header file 
```
#include"BST.h"
```

Here is a brief description of all the functions available in this header file :

### Step 1 : Create an Object of BST class and specify the data type in it :

`BST<data_type> obj_name;`

For exmaple,
`BST<char> obj3;` will create a BST in which each data will be of char type and object name is obj3. <br/> 
<br/>
Now you can freely use obj3, i.e, object name to invoke all the functions. Let's have a look at all the functions which are available to us. <br/>
<br/>

#### > insert
Inorder to insert any data in the binary search tree, follow this syntax :
```
obj_name.insert(data);
```
For example, `obj3.insert('D');` will insert D in the Binary Search Tree.
<br/>

#### > search
Inorder to check if any data in the BST, follow this syntax :
```
obj_name.search(data);
```
For example, `obj3.search('D');` will return 1 if it is present and 0 if it isn't present.
<br/>

#### > Delete
Inorder to Delete any data in the binary tree, follow this syntax :
```
obj_name.Delete(data);
```
For example, `obj3.Delete('D');` will delete D from the Binary Search Tree.
<br/>

### > Traversals 

Syntax for various traversals :

```
obj_name.traversal_name();
```
For Example :

```
    obj3.LevelOrder();
    cout<<endl;
    obj3.preorder();
    cout<<endl;
    obj3.postorder();
    cout<<endl;
    obj3.inorder();
    cout<<endl;
```
This will print all traversals as per the name.
<br/>

## Tree :

To use this header file copy the below given code in your header file 
```
#include"Tree.h"
```

Here is a brief description of all the functions available in this header file :

### Step 1 : Create an Object of tree class and specify the data type in it :

`tree<data_type> obj_name;`

For exmaple,
`tree<char> t;` will create a tree in which each data will be of char type and object name is t. <br/> 
<br/>
Now you can freely use t, i.e, object name to invoke all the functions. Let's have a look at all the functions which are available to us. <br/>
<br/>
#### > Print
To print in tree, follow this syntax :
```
obj_name.Print();
```
For example, `t.print();` will print in the Tree.
<br/>

