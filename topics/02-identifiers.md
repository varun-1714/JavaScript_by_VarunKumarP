# Identifiers 

### Naming convention for the element 

## Rules for Identifiers
- First Character should be alphabet or underscore( _ ) or $
- Subsequent can be letters or Digits or Underscore or $
- Identifiers are case sensitive
- Reserve keywords cannot be used as Identifiers

---

### In JavaScript there are three types of Identifiers according to data they hold

- **Let**
    - Identifier declared with Let keyword
    - It is avalible only within the block in which it is defined
    - Let keyword use when identifier declaration changed their value overtime or when the varaible need not be accessed outside the code block.
- **Const**
    - Identifier holds data that does not vary is called 'Constant' declare with __const__ keyword
    - value should intialized during declaration cannot be altered later
- **Var**
    - Identifiers hold data have function scope
    - They avalible only inside if they declared inside the function not work outside the function
    - They globally avalible if they were declared outside function

- **Let** Provides more predictable scoping and avoids common issues asscoiated with  **var**, such as accidental varaible re-declaration unintended access before declaration.

### Identifiers Differences :

| | **let** | **const** | **var** |
|-|---------|-----------|---------|
|Scope| block { } | block | function|
| re-declaration | not allowed | not allowed | allowed |
| re-assiging | allowed | not allowed | allowed|


