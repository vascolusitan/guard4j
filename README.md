# Guard4J
> Guard4J is a lightweight **Java** library that brings the power of **.NET Guard Clauses** to Java. 
> It follows a fail-fast strategy, ensuring that invalid data is rejected as early as possible, reducing unnecessary 
> resource consumption.

## Why Use Guard4J?
- ✅ **Fail-Fast Validation:** Prevents invalid data from propagating further into the application;
- ✅ **Lightweight & Efficient:** Minimal overhead, designed for high performance;
- ✅ **Type-Specific Guards:** Each data type has dedicated validation methods (e.g., GuardInt, GuardString, GuardUUID), 
preventing irrelevant checks (e.g., a negative String);
- ✅ **Improves Code Readability:** Eliminates boilerplate if conditions, making code more concise and expressive.

## What Does It Guard?
Guard4J provides validation methods for:
- **Primitive Types:** int, long, double, boolean, etc;
- **Common Java Types:** String, UUID, BigDecimal, etc.
