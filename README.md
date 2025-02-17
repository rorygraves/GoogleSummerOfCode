In this document, you can find a list of ideas that are proposed by the Scala Organisation for [Google Summer of Code 2025](https://summerofcode.withgoogle.com/).

## Application

If you are interested in becoming a contributor on any idea, please reach out to your potential mentor using their email address specified with the project. You can also reach Scala Center at [scala.center(at)epfl.ch](mailto:scala.center@epfl.ch).

If you would like to be a mentor and propose your own idea, please submit a PR editing this file (e.g. see [2024's projects](Past%20years%20ideas/2024.md)), adding your project to the list, following the format of other projects below.

## Rules

You can read the full rules of the program at the following links: [Rules](https://summerofcode.withgoogle.com/rules), [Terms and Conditions](https://summerofcode.withgoogle.com/terms/contributor), [Help](https://summerofcode.withgoogle.com/help).

And here are the requirements for the potential contributor's proposal: [Writing a proposal](https://google.github.io/gsocguides/student/writing-a-proposal).

However, here are some rules that we'd like to emphasize since they are not visible enough at the above links:

- The program is geared towards beginners first and foremost. It is intended to **be a learning experience** for people at the very beginning of their careers. It is also intended to **give an opportunity** to people who would otherwise not have one. It is NOT a freelance job. Therefore, when making an acceptance decision on a potential contributor, we will prioritize disadvantaged backgrounds and contributors at the very beginning of their careers.
- **IMPORTANT - EPFL Students**: Please note that, according to GSoC rules, there are restrictions on accepting students from an organization's host university. For Scala Center, the host university is EPFL. We can only accept up to 1 student from EPFL, so please take it into account if you're studying at EPFL and consider applying.

## Project Ideas

### Doodle Bitmap Convolutions

| Title                    | Doodle Bitmap Convolutions                                                                                              |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Link to Project          | https://github.com/creativescala/doodle/issues/94                                                                       |
| Brief Description        | Add support for bitmap convolutions to Doodle. The link has more, including a Github project laying out the steps.      |
| Expected Outcome         | Working code and documentation.                                                                                         |
| Prerequisites            | Some Scala knowledge.                                                                                                   |
| Ideal Prerequisites      | Basic knowledge of bitmap convolutions, some understanding of tagless final.                                            |
| Expected Difficulty      | Easy – straightforward task, path for execution visible right now, very little uncertainty                              |
| Expected Time Commitment | Medium project – 175 hours                                                                                              |
| Mentor                   | Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
| Co-mentor                |                                                                                                                         |

### Doodle Skia Backend

| Title                    | Doodle Skia Backend                                                                                                     |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Link to Project          | https://github.com/creativescala/doodle/issues/175                                                                      |
| Brief Description        | Add a Skia backend for Doodle, using the Skiaj bindings.                                                                |
| Expected Outcome         | Working code and documentation.                                                                                         |
| Prerequisites            | Some Scala knowledge.                                                                                                   |
| Ideal Prerequisites      | Some understanding of type classes or tagless final.                                                                    |
| Expected Difficulty      | Easy – straightforward task, path for execution visible right now, very little uncertainty                              |
| Expected Time Commitment | Medium project – 175 hours                                                                                              |
| Mentor                   | Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
| Co-mentor                |                                                                                                                         |

### Krop Template Engine

| Title                    | Krop Template Engine                                                                                                    |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Link to Project          | https://github.com/creativescala/krop/issues/14                                                                         |
| Brief Description        | Create an HTML template engine for the Krop web framework.                                                              |
| Expected Outcome         | Working code and documentation.                                                                                         |
| Prerequisites            | Intermediate Scala knowledge and basic HTML knowledge.                                                                  |
| Ideal Prerequisites      | An understanding of parsing.                                                                                            |
| Expected Difficulty      | Medium – some design decisions need to be made and the implementation is not straightforward.                           |
| Expected Time Commitment | Medium project – 175 hours                                                                                              |
| Mentor                   | Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
| Co-mentor                |                                                                                                                         |

### Scaladex: Support for Compiler Plugins

| Title                   | Scaladex: Support for Compiler Plugins |
| ----------------------- | -------------------------------- |
| Link to Project         | https://github.com/scalacenter/scaladex/ |
| Brief Description       | Add support for compiler plugins in Scaladex, the index website of open source Scala artifacts. Adapt the UI of the front page, search page and project page to allow searching, and browsing compiler plugins and their versions. See full description in [scalacenter/scaladex#865](https://github.com/scalacenter/scaladex/issues/865) |
| Expected Outcome        | Scaladex should index compiler plugin artifacts, such as [org.typelevel:kind-projector_2.13.16:0.13.3](https://repo1.maven.org/maven2/org/typelevel/kind-projector_2.13.16/0.13.3/). It should show them as a separate platform on the front page, search page and project page. |
| Prerequisites           | Some experience with Scala and SQL. Good knowledge about HTML and css |
| Ideal Prerequisites     | Some knowledge of the Scala ecosystem, such as Scala platforms and binary versions |
| Expected Difficulty     | Medium |
| Expected Time Commitment| Medium project - 175 hours |
| Spoken Language         | English |
| Mentor                  | Kannupriya Kalra ([LinkedIn](https://www.linkedin.com/in/kannupriyakalra/), Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com)) |
| Co-mentor               | Adrien Piquerez (GitHub: [@adpi2](https://github.com/adpi2), Email: [adrien.piquerez@gmail.com](mailto:adrien.piquerez@gmail.com)) |

### Typelevel Projects

For project ideas relating to the Typelevel ecosystem in the categories of AI/ML, serverless, data streaming, observability, and systems programming, please visit https://typelevel.org/gsoc/ideas/.

### LLM4S - Implement an agentic toolkit for Large Language Models

|Title                   |                                   |
|------------------------|------------------------------------------|
|Link to Project         | https://github.com/rorygraves/llm4s                                        |
|Brief Description       | LLM4S is creating a Large Language Model (LLM) toolkit for Scala.  This project uses the power of Scala to make building LLM based applications easier.  LLMs can be used in an agentic style where the LLM is allowed to call provided tools to access resources (such as reading a webpage, or calling an API service to perform a task).  The goal of this project is to create a standard toolkit that developers can use when building agentic agents. |
|Expected Outcome        | LLM4S should have a useful set of tools integrated for LLM use, such as file or web browser tools to be used by applications built with LLM4S. |
|Prerequisites           | Some exerience of Scala and LLMs. |
|Expected Difficulty     | Medium  |
|Expected Time Commitment| Medium project - 175 hours |
|Spoken Language         | English |
|Mentor                  | Kannupriya Kalra ([LinkedIn](https://www.linkedin.com/in/kannupriyakalra/), Email: [kannupriyakalra@gmail.com](mailto:kannupriyakalra@gmail.com)) |
|Co-mentor               | Rory Graves ([LinkedIn](https://www.linkedin.com/in/roryjgraves/), Email: [rory.graves@fieldmark.co.uk](mailto:rory.graves@fieldmark.co.uk)) |


### Template

|Title                   | |
|------------------------|--------------------------------|
|Link to Project         |Provide a link to a website or a Git repository of your project.|
|Brief Description       |Please describe in a few sentences what the project is about.|
|Expected Outcome        |Specify the success criteria for the project. What are the deliverables, how do you know that it is done?|
|Prerequisites           |What minimal skills and knowledge the contributor needs to have to succeed on this project?|
|Expected Difficulty     |Easy, Medium of Hard|
|Expected Time Commitment|Can be either: "Medium project - 175 hours" or "Large project - 350 hours"|
|Spoken Language         |English|
|Mentor                  |FirstName LastName (GitHub: [@foo](https://github.com/foo), Email: [foo@gmail.com](mailto:foo@gmail.com))|
|Co-mentor               |FirstName LastName (GitHub: [@foo](https://github.com/foo), Email: [foo@gmail.com](mailto:foo@gmail.com))|

