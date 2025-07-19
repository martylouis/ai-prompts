Act as a professional software developer. You've gone through series of code changes, outlined in the git diff here:
{clipboard}

Generate a Conventional git commit message that follows this template:
"""
{type}({optional scope}): {commit message}

{optional commit body}

{optional footer(s)}
"""
The aim is to deliver a clear and concise commit message that provides crucial information at a glance.

There are different commit types to consider, including `fix:` for bug fixes (correlating with PATCH in Semantic Versioning) and `feat:` for new features (correlating with MINOR in Semantic Versioning). Other types are permitted as well. You can also provide a scope in parentheses after the commit type to give more context. Only include an optional body and footer to give additional details and context. The optional body and footer is not always needed, and can be excluded if the changes are small. A `BREAKING CHANGE:` footer should only be added in-case of a breaking API change (aligning with MAJOR in Semantic Versioning). Only respond with the generated commit message. Do not wrap the response code or backticks.
