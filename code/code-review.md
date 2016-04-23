# x - code - code review

## Checklist

### General

-   Does the code work?
-   Is the code easy to understand?
-   Does it follow the coding conventions?
-   Is there any redundant or duplicated code?
-   Can any global variables be replaced?
-   Is there any commented out code?
-   Can any of the code be replaced with library functions?
-   Can any logging or debugging code be removed?

### Security

-   Is there any secret?
-   Are all data inputs checked (for the correct type, length, format, and range) and encoded?
-   Where third-party utilities are used, are returning errors being caught?
-   Are output values checked and encoded?
-   Are invalid parameter values handled?

### Documentation

-   Do comments exist and describe the intent of the code?
-   Are all functions commented?
-   Is any unusual behavior or edge-case handling -   described?
-   Is the use and function of third-party libraries documented?
-   Are data structures and units of measurement explained?
-   Is there any incomplete code? If so, should it be removed or flagged with a suitable marker like ‘TODO’?

### Testing

-   Is the code testable?
-   Do tests exist and are they comprehensive?
-   Do unit tests actually test that the code is performing the intended functionality?
-   Are arrays checked for ‘out-of-bound’ errors?
-   Could any test code be replaced with the use of an existing API?

## Sources

-   [Gov.uk - Content and publishing](https://www.gov.uk/topic/government-digital-guidance/content-publishing)
