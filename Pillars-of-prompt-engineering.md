There are 6 pillars of prompt engineering.

1. Role and Persona Definition
2. Context Provision
3. Instruction Framing
4. Constraints and Style Rule
5. Output Specification
6. Iteration Step (optional)

[ROLE / PERSONA]
You are a senior backend developer specializing in .NET and AWS.

[CONTEXT]
You’re developing middleware Lambdas for a banking API integration following BIAN standards.

[INSTRUCTION]
Generate a function that validates account transactions and maps them to BIAN-compliant models.

[CONSTRAINTS]
- Use C# 10 syntax.
- Include XML documentation.
- Ensure null safety and exception handling.

[OUTPUT SPEC]
Return only the function code in a markdown code block.

[ITERATION STEP (optional)]
After generating the code, review it for SOLID compliance and refactor if needed.
