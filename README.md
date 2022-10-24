# Code Review Checklist

In the following a code review checklist is presented where each section focuses one aspect of software/code quality.

## Functional Suitability ✔
- [ ] __Functional correctness__: Does the solution correctly do what it does?
- [ ] __Functional completeness__: Does the solution do all that it should do?

## Code Readability 📚
- [ ] __Naming__: Do variables, methods and classes/types have appropriate naming?
- [ ] __Commenting__: Is the code self-documenting or else does it have sufficient comments?
- [ ] __Code complexity__: Are methods, functions, modules or procedures small, concise, coherent and understandable?

## Code Maintainability 🛠
- [ ] __Code complexity__: Do methods have a low [cognitive complexity](https://www.sonarsource.com/docs/CognitiveComplexity.pdf) score?
- [ ] __Code Duplication__: Does the code adhere to the DRY principle?
- [ ] Does the code have appropriate folder structure?
- [ ] Does the code appropriately apply object-oriented principles?
- [ ] Do classes have high cohesion and low coupling?
- [ ] Does the code adhere to the YAGNI principle?
- [ ] Does the code adhere to the KISS principle?
- [ ] Does the code adhere to [SOLID](https://github.com/harrymt/SOLID-principles#single-responsibility-principle) principles?

## Troubleshooting, Debugging and Fault Detection ❌ 
- [ ] __Error Handling__: Is error handling done the correct way?
- [ ] __Logging__: Should any logging or debugging information be added or removed?
- [ ] __Error Handling & Logging__: Are error messages user-friendly?

## Security and Data Privacy 🔐
- [ ] Does the code hold any hard coded passwords or keys?
- [ ] Is the solution revealing any sensitive data to non-admin users?

## Performance ⚙
- [ ] Are there any critical performance improvements required?


## Usability 🤳🏻
- [ ] Is the implemented solution well designed from a usability perspective?
- [ ] Is the solution well documented?


## Testing and Testability ✅
- [ ] Is the code testable?
- [ ] Does the code have automated tests (unit/integration/system tests)?
- [ ] Do the tests have adequate code coverage?

# Code Review Code of Conduct: 

Code review is a dynamic which allow for team members to proofread each other’s code and to ensure a code delivered is a code weighed. Developer bias can sometimes lead to unintentional or intentional quality compromises which can lead to technical debt in a codebases. Code reviews are inherently a roleplay interaction and as such for it to work it is important for a code reviewer to adhere to certain guidelines to facilitate constructive exchanges.

## Acceptable
When reviewing someone else's code:
- It is acceptable to pass on comments on _standards_. 📐 Coding standards are a set of measurable code quality requirements which is agreed upon by a group of developers that includes both the reviewer and code author. It is important to distinguish coding standards from coding preferences.

## Not Acceptable
When reviewing someone else's code: 
- Do not pass on comments on _style_! 💅🏻 Everyone has a coding style which matches their preferences and coding experience. Code reviewers should be accepting of the diversity in coding styles. If a reviewer inadvertently forces an author to change their coding style, the author may feel they no longer own their code and as such may no longer be able to take responsibility for their code as effectively.

## References
<a id="1">[1]</a> 
[Code Review: A Comprehensive Checklist](https://dev.to/alexomeyer/code-review-a-comprehensive-checklist-5gnm)

<a id="2">[2]</a>
[GUIDE: code review](https://github.com/reiver/guide-code-review) by [Charles Iliya Krempeaux](https://github.com/reiver)

<a id="3">[3]</a>
[Code Review Checklist](https://github.com/mgreiler/code-review-checklist) by [Michaela Greiler](https://github.com/mgreiler)





