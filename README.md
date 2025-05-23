# Table of Contents

- [`1 Introduction to Robot Framework`](website/docs/chapter-01/00_overview.md)
- [`1.1 Purpose / Use Cases`](website/docs/chapter-01/01_purpose.md)
- LO-1.1 (K1) Recall the two main use cases of Robot Framework
- [`1.1.1 Test Automation`](website/docs/chapter-01/01_purpose.md#111-test-automation)
  - LO-1.1.1 (K1) Recall the test levels Robot Framework is mostly used for
  - [`1.1.1.1 Synthetic Monitoring`](website/docs/chapter-01/01_purpose.md#1111-synthetic-monitoring)
- [`1.1.2 Robotic Process Automation (RPA)`](website/docs/chapter-01/01_purpose.md#112-robotic-process-automation-rpa)
- [`1.2 Architecture of Robot Framework`](website/docs/chapter-01/02_architecture.md)
- [`1.2.1 Robot Framework and the gTAA (Generic Test Automation Architecture)`](website/docs/chapter-01/02_architecture.md#121-robot-framework-and-the-gtaa-generic-test-automation-architecture)
  - LO-1.2.1 (K1) Recall the layers of the Generic Test Automation Architecture (gTAA) and their corresponding components in Robot Framework
- [`1.2.2 What is Robot Framework & What It Is Not`](website/docs/chapter-01/02_architecture.md#122-what-is-robot-framework--what-it-is-not)
  - LO-1.2.2 (K1) Recall what is part of Robot Framework and what is not
- [`1.2.3 Technology & Prerequisites`](website/docs/chapter-01/02_architecture.md#123-technology--prerequisites)
  - LO-1.2.3 (K1) Recall the technology Robot Framework is built on and the prerequisites for running it
- [`1.3 Basic Syntax & Structure`](website/docs/chapter-01/03_syntax.md)
- LO-1.3 (K1) Recall the key attributes of the syntax that makes Robot Framework simple and human-readable
- [`1.3.1 What are Test Cases / Tasks?`](website/docs/chapter-01/03_syntax.md#131-what-are-test-cases--tasks)
- [`1.3.2 Files & Directories`](website/docs/chapter-01/03_syntax.md#132-files--directories)
- [`1.3.3 What are Keywords?`](website/docs/chapter-01/03_syntax.md#133-what-are-keywords)
  - LO-1.3.3 (K2) Explain the difference between User Keywords and Library Keywords
- [`1.3.4 Resource Files & Libraries`](website/docs/chapter-01/03_syntax.md#134-resource-files--libraries)
  - LO-1.3.4 (K1) Recall the difference between Resource Files and Libraries and their artifacts
- [`1.4 Specification Styles`](website/docs/chapter-01/04_styles.md)
- LO-1.4 (K1) Recall the three specification styles of Robot Framework
- [`1.4.1 Keyword-Driven Specification`](website/docs/chapter-01/04_styles.md#141-keyword-driven-specification)
  - LO-1.4.1 (K2) Understand the basic concepts of Keyword-Driven Specification
- [`1.4.2 Behavior-Driven Specification`](website/docs/chapter-01/04_styles.md#142-behavior-driven-specification)
  - LO-1.4.2 (K2) Understand the basic concepts of Behavior-Driven Specification
- [`1.4.3 Comparing Keyword-Driven and Behavior-Driven Specification`](website/docs/chapter-01/04_styles.md#143-comparing-keyword-driven-and-behavior-driven-specification)
  - LO-1.4.3 (K1) Recall the differences between Keyword-Driven and Behavior-Driven Specification
- [`1.4.4 Data-Driven Specification`](website/docs/chapter-01/04_styles.md#144-data-driven-specification)
  - LO-1.4.4 (K1) Recall the purpose of Data-Driven Specification
- [`1.5 Organization and Licensing`](website/docs/chapter-01/05_organization.md)
- [`1.5.1 Open Source License`](website/docs/chapter-01/05_organization.md#151-open-source-license)
  - LO-1.5.1 (K1) Recall the type of open-source license under which Robot Framework is distributed
- [`1.5.2 About the Robot Framework Foundation`](website/docs/chapter-01/05_organization.md#152-about-the-robot-framework-foundation)
  - LO-1.5.2 (K1) List and recall the key objectives and organizational form of the Robot Framework Foundation
- [`1.5.3 Robot Framework Webpages`](website/docs/chapter-01/05_organization.md#153-robot-framework-webpages)
  - LO-1.5.3 (K1) Recall the official webpages for Robot Framework and its resources
- [`2 Getting Started with Robot Framework`](website/docs/chapter-02/00_overview.md)
- [`2.1 Suite File & Tree Structure`](website/docs/chapter-02/01_suitefile.md)
- LO-2.1 (K2) Understand which files and directories are considered suites and how they are structured in a suite tree.
- [`2.1.1 Suite Files`](website/docs/chapter-02/01_suitefile.md#211-suite-files)
  - LO-2.1.1 (K1) Recall the conditions and requirements for a file to be considered a Suite file
- [`2.1.2 Sections and Their Artifacts`](website/docs/chapter-02/01_suitefile.md#212-sections-and-their-artifacts)
  - LO-2.1.2 (K1) Recall the available sections in a suite file and their purpose.
  - [`2.1.2.1 Introduction in `*** Settings ***` Section`](website/docs/chapter-02/01_suitefile.md#2121-introduction-in--settings--section)
    - LO-2.1.2.1-1 (K1) Recall the available settings in a suite file.
    - LO-2.1.2.1-2 (K2) Understand the concepts of suite settings and how to define them.
  - [`2.1.2.2 Introduction in `*** Variables ***` Section`](website/docs/chapter-02/01_suitefile.md#2122-introduction-in--variables--section)
    - LO-2.1.2.2 (K1) Recall the purpose of the `*** Variables ***` section.
  - [`2.1.2.3 Introduction in `*** Test Cases ***` or `*** Tasks ***` Section`](website/docs/chapter-02/01_suitefile.md#2123-introduction-in--test-cases--or--tasks--section)
    - LO-2.1.2.3 (K2) Understand the purpose of the `*** Test Cases ***` or `*** Tasks ***` section.
  - [`2.1.2.4 Introduction in `*** Keywords ***` Section`](website/docs/chapter-02/01_suitefile.md#2124-introduction-in--keywords--section)
    - LO-2.1.2.4 (K2) Understand the purpose and limitations of the `*** Keywords ***` section.
  - [`2.1.2.5 Introduction in `*** Comments ***` Section`](website/docs/chapter-02/01_suitefile.md#2125-introduction-in--comments--section)
- [`2.2 Basic Suite File Syntax`](website/docs/chapter-02/02_suitefile_syntax.md)
- LO-2.2 (K2) Understand the basic syntax of test cases and tasks.
- [`2.2.1 Separation and Indentation`](website/docs/chapter-02/02_suitefile_syntax.md#221-separation-and-indentation)
  - LO-2.2.1 (K3) Understand and apply the mechanics of indentation and separation in Robot Framework.
- [`2.2.2 Line Breaks, Continuation and Empty Lines`](website/docs/chapter-02/02_suitefile_syntax.md#222-line-breaks-continuation-and-empty-lines)
  - LO-2.2.2 (K3) Be able to use line breaks and continuation in a statement.
- [`2.2.3 In-line Comments`](website/docs/chapter-02/02_suitefile_syntax.md#223-in-line-comments)
  - LO-2.2.3 (K3) Be able to add in-line comments to suites.
- [`2.2.4 Escaping of Control Characters`](website/docs/chapter-02/02_suitefile_syntax.md#224-escaping-of-control-characters)
  - LO-2.2.4 (K2) Understand how to escape control characters in Robot Framework.
- [`2.2.5 Example Suite File`](website/docs/chapter-02/02_suitefile_syntax.md#225-example-suite-file)
  - LO-2.2.5 (K2) Understand the structure of a basic suite file.
- [`2.3 Executing Robot`](website/docs/chapter-02/03_executing.md)
- LO-2.3 (K1) Recall the three components of the Robot Framework CLI.
- [`2.3.1 `robot` command & help`](website/docs/chapter-02/03_executing.md#231-robot-command--help)
  - LO-2.3.1 (K2) Understand how to run the `robot` command and its basic usage.
- [`2.3.2 Execution Artifacts`](website/docs/chapter-02/03_executing.md#232-execution-artifacts)
  - LO-2.3.2 (K2) Explain the execution artifacts generated by Robot Framework.
- [`2.3.3 Status`](website/docs/chapter-02/03_executing.md#233-status)
  - LO-2.3.3 (K1) Recall the four different status labels used by Robot Framework.
  - [`2.3.3.1 PASS`](website/docs/chapter-02/03_executing.md#2331-pass)
    - LO-2.3.3.1 (K2) Understand when an element is marked as `PASS`.
  - [`2.3.3.2 FAIL`](website/docs/chapter-02/03_executing.md#2332-fail)
    - LO-2.3.3.2 (K2) Understand when an element is marked as `FAIL`.
- [`2.3.4 Logging possibilities (Log vs Console)`](website/docs/chapter-02/03_executing.md#234-logging-possibilities-log-vs-console)
  - LO-2.3.4 (K2) Understand the difference between log messages and console output.
- [`2.4 Keyword Imports`](website/docs/chapter-02/04_keyword_imports.md)
- [`2.4.1 Libraries`](website/docs/chapter-02/04_keyword_imports.md#241-libraries)
  - LO-2.4.1-1 (K1) Recall the purpose of keyword libraries and how to import them.
  - LO-2.4.1-2 (K1) Recall the three types of libraries in Robot Framework.
- [`2.4.2 Resource Files`](website/docs/chapter-02/04_keyword_imports.md#242-resource-files)
  - LO-2.4.2-1 (K1) Recall the purpose of resource files.
  - LO-2.4.2-2 (K3) Use resource files to import new keywords.
- [`2.4.3 Import Paths`](website/docs/chapter-02/04_keyword_imports.md#243-import-paths)
  - LO-2.4.3 (K2) Understand the different types of paths that can be used to import libraries and resource files.
- [`2.5 Keyword Interface and Documentation`](website/docs/chapter-02/05_keyword_interface.md)
- LO-2.5 (K2) Understand the structure of keyword interfaces and how to interpret keyword documentation.
- [`2.5.1 Documented Keyword Information`](website/docs/chapter-02/05_keyword_interface.md#251-documented-keyword-information)
  - LO-2.5.1 (K1) Recall the information that can be found in a keyword documentation.
  - [`2.5.1.1 Example Keyword `Should Be Equal``](website/docs/chapter-02/05_keyword_interface.md#2511-example-keyword-should-be-equal)
  - [`2.5.1.2 Example Keyword `Run Process``](website/docs/chapter-02/05_keyword_interface.md#2512-example-keyword-run-process)
  - [`2.5.1.3 Example Keyword `Get Regexp Matches``](website/docs/chapter-02/05_keyword_interface.md#2513-example-keyword-get-regexp-matches)
- [`2.5.2 Keyword Arguments`](website/docs/chapter-02/05_keyword_interface.md#252-keyword-arguments)
  - LO-2.5.2 (K2) Understand the difference between argument kinds.
  - [`2.5.2.1 Mandatory Arguments`](website/docs/chapter-02/05_keyword_interface.md#2521-mandatory-arguments)
    - LO-2.5.2.1 (K2) Understand the concept of mandatory arguments and how they are documented.
  - [`2.5.2.2 Optional Arguments`](website/docs/chapter-02/05_keyword_interface.md#2522-optional-arguments)
    - LO-2.5.2.2 (K2) Understand the concept of optional arguments and how they are documented.
  - [`2.5.2.3 Embedded Arguments`](website/docs/chapter-02/05_keyword_interface.md#2523-embedded-arguments)
    - LO-2.5.2.3 (K1) Recall the concept of keywords with embedded arguments used in Behavior-Driven Specification and how they are documented.
  - [`2.5.2.4 Positional or Named Arguments`](website/docs/chapter-02/05_keyword_interface.md#2524-positional-or-named-arguments)
    - LO-2.5.2.4 (K1) Recall how "Positional or Named Arguments" are marked in the documentation and their use case.
  - [`2.5.2.5 Variable Number of Positional Arguments`](website/docs/chapter-02/05_keyword_interface.md#2525-variable-number-of-positional-arguments)
    - LO-2.5.2.5 (K1) Recall how "Variable Number of Positional Arguments" are marked in the documentation and their use case.
  - [`2.5.2.6 Named-Only Arguments`](website/docs/chapter-02/05_keyword_interface.md#2526-named-only-arguments)
    - LO-2.5.2.6 (K1) Recall what properties "Named-Only Arguments" have and how they are documented.
  - [`2.5.2.7 Free Named Arguments`](website/docs/chapter-02/05_keyword_interface.md#2527-free-named-arguments)
    - LO-2.5.2.7 (K1) Recall how free named arguments are marked in documentation.
  - [`2.5.2.8 Argument Types`](website/docs/chapter-02/05_keyword_interface.md#2528-argument-types)
    - LO-2.5.2.8 (K2) Understand the concept of argument types and automatic type conversion.
  - [`2.5.2.9 Return Types`](website/docs/chapter-02/05_keyword_interface.md#2529-return-types)
    - LO-2.5.2.9 (K2) Understand the concept of return type hints.
- [`2.5.3 Keyword Documentation & Examples`](website/docs/chapter-02/05_keyword_interface.md#253-keyword-documentation--examples)
  - LO-2.5.3 (K2) Understand how to read keyword documentation and how to interpret the examples.
- [`2.6 Writing Test|Task and Calling Keywords`](website/docs/chapter-02/06_writing_test.md)
- LO-2.6 (K2) Understand how to call imported keywords and how to structure keyword calls.
- [`2.6.1 Positional Arguments`](website/docs/chapter-02/06_writing_test.md#261-positional-arguments)
  - LO-2.6.1 (K2) Understand the concept of how to set argument values positionally.
- [`2.6.2 Named Arguments`](website/docs/chapter-02/06_writing_test.md#262-named-arguments)
  - LO-2.6.2 (K2) Understand the concept of named arguments and how to set argument values by their name.
- [`2.6.3 Embedded Arguments / Using Behavior-Driven Specification`](website/docs/chapter-02/06_writing_test.md#263-embedded-arguments--using-behavior-driven-specification)
  - LO-2.6.3 (K1) Recall how to use embedded arguments.
- [`3 Keyword Design, Variables, and Resource Files`](website/docs/chapter-03/00_overview.md)
- [`3.1 Resource File Structure`](website/docs/chapter-03/01_resource_file.md)
- [`3.1.1 Sections in Resource Files`](website/docs/chapter-03/01_resource_file.md#311-sections-in-resource-files)
- [`3.2 Variables`](website/docs/chapter-03/02_variables.md)
- LO-3.2-1 (K2) Understand how variables in Robot Framework are used to store and manage data
- LO-3.2-2 (K1) Recall the relevant five different ways to create and assign variables
- [`3.2.1 Variable Syntax and Access Types`](website/docs/chapter-03/02_variables.md#321-variable-syntax-and-access-types)
  - LO-3.2.1-1 (K1) Recall the four syntactical access types to variables with their prefixes
  - LO-3.2.1-2 (K1) Recall the basic syntax of variables
- [`3.2.2 `*** Variables ***` Section`](website/docs/chapter-03/02_variables.md#322--variables--section)
  - LO-3.2.2-1 (K3) Create variables in the Variables section
  - LO-3.2.2-2 (K3) Use the correct variable prefixes for assigning and accessing variables
  - [`3.2.2.1 Scalar Variable Definition`](website/docs/chapter-03/02_variables.md#3221-scalar-variable-definition)
    - LO-3.2.2.1-1 (K3) Create and assign scalar variables
    - LO-3.2.2.1-2 (K2) Understand how multiple lines can be used to define scalar variables
  - [`3.2.2.2 Primitive Data Types`](website/docs/chapter-03/02_variables.md#3222-primitive-data-types)
    - LO-3.2.2.2 (K2) Understand how to access primitive data types
  - [`3.2.2.3 List Variable Definition`](website/docs/chapter-03/02_variables.md#3223-list-variable-definition)
    - LO-3.2.2.3 (K2) Understand how to set and access data in list variables
  - [`3.2.2.4 Dictionary Variable Definition`](website/docs/chapter-03/02_variables.md#3224-dictionary-variable-definition)
    - LO-3.2.2.4 (K2) Understand how to set and access data in dict variables
- [`3.2.3 Return values from Keywords`](website/docs/chapter-03/02_variables.md#323-return-values-from-keywords)
  - LO-3.2.3 (K3) Be able to assign return values from keywords to variables
  - [`3.2.3.1 Assigning to Scalar Variables`](website/docs/chapter-03/02_variables.md#3231-assigning-to-scalar-variables)
- [`3.2.4 `VAR` Statement`](website/docs/chapter-03/02_variables.md#324-var-statement)
  - LO-3.2.4 (K2) Understand how to create variables using the VAR statement
- [`3.2.5 Variable Scope Introduction`](website/docs/chapter-03/02_variables.md#325-variable-scope-introduction)
  - LO-3.2.5 (K2) Understand how `local` and `suite` scope variables are created
- [`3.3 User Keyword Definition & Arguments`](website/docs/chapter-03/03_user_keyword.md)
- [`3.3.1 `*** Keywords ***` Section`](website/docs/chapter-03/03_user_keyword.md#331--keywords--section)
- [`3.3.2 User Keyword Names`](website/docs/chapter-03/03_user_keyword.md#332-user-keyword-names)
  - LO-3.3.2 (K1) Recall the rules how keyword names are matched.
- [`3.3.3 User Keyword Settings`](website/docs/chapter-03/03_user_keyword.md#333-user-keyword-settings)
  - LO-3.3.3 (K1) Recall all available settings and their purpose for User Keywords
- [`3.3.4 User Keyword Documentation`](website/docs/chapter-03/03_user_keyword.md#334-user-keyword-documentation)
  - LO-3.3.4 (K1) Recall the significance of the first logical line and in keyword documentation for the log file.
- [`3.3.5 User Keyword Arguments`](website/docs/chapter-03/03_user_keyword.md#335-user-keyword-arguments)
  - LO-3.3.5 (K2) Understand the purpose and syntax of the [Arguments] setting in User Keywords.
  - [`3.3.5.1 Defining Mandatory Arguments`](website/docs/chapter-03/03_user_keyword.md#3351-defining-mandatory-arguments)
    - LO-3.3.5.1-1 (K1) Recall what makes an argument mandatory in a user keyword.
    - LO-3.3.5.1-2 (K3) Define User Keywords with mandatory arguments.
  - [`3.3.5.2 Defining Optional Arguments`](website/docs/chapter-03/03_user_keyword.md#3352-defining-optional-arguments)
    - LO-3.3.5.2-1 (K1) Recall how to define optional arguments in a user keyword.
    - LO-3.3.5.2-2 (K3) Define User Keywords with optional arguments.
  - [`3.3.5.3 Defining Embedded Arguments`](website/docs/chapter-03/03_user_keyword.md#3353-defining-embedded-arguments)
    - LO-3.3.5.3-1 (K2) Describe how embedded arguments are replaced by actual values during keyword execution.
    - LO-3.3.5.3-2 (K2) Understand the role of embedded arguments in Behavior-Driven Development (BDD) style.
  - [`3.3.5.4 Other Argument Kinds`](website/docs/chapter-03/03_user_keyword.md#3354-other-argument-kinds)
- [`3.3.6 RETURN Statement`](website/docs/chapter-03/03_user_keyword.md#336-return-statement)
  - LO-3.3.6-1 (K2) Understand how the `RETURN` statement passes data between different keywords.
  - LO-3.3.6-2 (K3) Use the `RETURN` statement to return values from a user keyword and assign it to a variable.
- [`3.3.7 Keyword Conventions`](website/docs/chapter-03/03_user_keyword.md#337-keyword-conventions)
  - LO-3.3.7 (K1) Recall the naming conventions for user keywords.
- [`3.4 Using Data-Driven Specification`](website/docs/chapter-03/04_datadriven.md)
- LO-3.4 (K2) Understand the basic concept and syntax of Data-Driven Specification
- [`3.4.1 Test|Task Templates`](website/docs/chapter-03/04_datadriven.md#341-testtask-templates)
  - LO-3.4.1-1 (K2) Understand how to define and use test|task templates
  - LO-3.4.1-2 (K1) Recall the differences between the two different approaches to define Data-Driven Specification
  - [`3.4.1.1 Multiple Named Test|Task With One Template`](website/docs/chapter-03/04_datadriven.md#3411-multiple-named-testtask-with-one-template)
    - LO-3.4.1.1 (K1) Recall the syntax and properties of multiple named test|task with one template
  - [`3.4.1.2 Named Test|Task With Multiple Data Rows:`](website/docs/chapter-03/04_datadriven.md#3412-named-testtask-with-multiple-data-rows)
    - LO-3.4.1.2 (K1) Recall the syntax and properties of named test|task with multiple data rows
- [`3.5 Advanced Importing of Keywords and Naming Conflicts`](website/docs/chapter-03/05_advanced_importing.md)
- LO-3.5 (K1) Recall that naming conflicts can arise from the import of multiple resource files.
- [`3.5.1 Importing Hierarchies`](website/docs/chapter-03/05_advanced_importing.md#351-importing-hierarchies)
  - LO-3.5.1 (K2) Understand how transitive imports of resource files and libraries work.
- [`3.5.2 Library Configuration`](website/docs/chapter-03/05_advanced_importing.md#352-library-configuration)
  - LO-3.5.2 (K3) Be able to configure a library import using arguments.
- [`3.5.3 Naming Conflicts`](website/docs/chapter-03/05_advanced_importing.md#353-naming-conflicts)
  - LO-3.5.3 (K2) Explain how naming conflicts can happen and how to mitigate them.
- [`4 Advanced Structuring and Execution`](website/docs/chapter-04/00_overview.md)
- [`4.1 Setups (Suite, Test|Task, Keyword)`](website/docs/chapter-04/01_setups.md)
- LO-4.1-1 (K1) Recall the purpose and benefits of Setups in Robot Framework
- LO-4.1-2 (K1) Recall the different levels where a Setup can be defined
- [`4.1.1 Suite Setup`](website/docs/chapter-04/01_setups.md#411-suite-setup)
  - LO-4.1.1-1 (K1) Recall key characteristics, benefits, and syntax of Suite Setup
  - LO-4.1.1-2 (K2) Understand when Suite Setup is executed and used
- [`4.1.2 Test|Task Setup`](website/docs/chapter-04/01_setups.md#412-testtask-setup)
  - LO-4.1.2-1 (K1) Recall key characteristics, benefits, and syntax of Test Setup
  - LO-4.1.2-2 (K2) Understand when Test|Task Setup is executed and used
- [`4.1.3 Keyword Setup`](website/docs/chapter-04/01_setups.md#413-keyword-setup)
  - LO-4.1.3 (K1) Recall key characteristics and syntax of Keyword Setup
- [`4.2 Teardowns (Suite, Test|Task, Keyword)`](website/docs/chapter-04/02_teardowns.md)
- LO-4.2-1 (K2) Understand the different levels where and how Teardowns can be defined and when they are executed
- LO-4.2-2 (K1) Recall the typical use cases for using Teardowns
- [`4.2.1 Suite Teardown`](website/docs/chapter-04/02_teardowns.md#421-suite-teardown)
  - LO-4.2.1-1 (K1) Recall key characteristics, benefits, and syntax of Suite Teardown
  - LO-4.2.1-2 (K2) Understand when Suite Teardown is executed and used
- [`4.2.2 Test|Task Teardown`](website/docs/chapter-04/02_teardowns.md#422-testtask-teardown)
  - LO-4.2.2-1 (K1) Recall key characteristics, benefits, and syntax of Test|Task Teardown
  - LO-4.2.2-2 (K2) Understand when Test|Task Teardown is executed and used
- [`4.2.3 Keyword Teardown`](website/docs/chapter-04/02_teardowns.md#423-keyword-teardown)
  - LO-4.2.3 (K1) Recall key characteristics, benefits, and syntax of Keyword Teardown
- [`4.3 Initialization Files`](website/docs/chapter-04/03_init_files.md)
- LO-4.3 (K1) Recall how to define an Initialization Files and its purpose
- [`4.3.1 Purpose of Initialization Files`](website/docs/chapter-04/03_init_files.md#431-purpose-of-initialization-files)
- [`4.3.2 Suite Setup and Suite Teardown of Initialization Files`](website/docs/chapter-04/03_init_files.md#432-suite-setup-and-suite-teardown-of-initialization-files)
  - LO-4.3.2 (K2) Understand the execution order of Suite Setup and Suite Teardown in Initialization Files and their sub-suites and tests|tasks
- [`4.3.3 Allowed Sections in Initialization Files`](website/docs/chapter-04/03_init_files.md#433-allowed-sections-in-initialization-files)
  - LO-4.3.3 (K1) Recall the allowed sections and their content in Initialization Files
- [`4.3.4 Example of an Initialization File`](website/docs/chapter-04/03_init_files.md#434-example-of-an-initialization-file)
- [`4.4 Test|Task Tags and Filtering Execution`](website/docs/chapter-04/04_tags.md)
- LO-4.4 (K1) Recall the purpose of Test|Task Tags in Robot Framework
- [`4.4.1 Assigning Tags to Tests|Tasks`](website/docs/chapter-04/04_tags.md#441-assigning-tags-to-teststasks)
  - LO-4.4.1 (K1) Recall the syntax and different ways to assign tags to tests|tasks
- [`4.4.2 Using Tags to Filter Execution`](website/docs/chapter-04/04_tags.md#442-using-tags-to-filter-execution)
  - LO-4.4.2 (K2) Understand how to filter tests|tasks using the command-line interface of Robot Framework
  - [`4.4.2.1 Including Tests|Tasks by Tags`](website/docs/chapter-04/04_tags.md#4421-including-teststasks-by-tags)
  - [`4.4.2.2 Excluding Tests|Tasks by Tags`](website/docs/chapter-04/04_tags.md#4422-excluding-teststasks-by-tags)
  - [`4.4.2.3 Combining Include and Exclude Options`](website/docs/chapter-04/04_tags.md#4423-combining-include-and-exclude-options)
  - [`4.4.2.4 Using Tag Patterns`](website/docs/chapter-04/04_tags.md#4424-using-tag-patterns)
- [`4.4.3 Reserved Tags`](website/docs/chapter-04/04_tags.md#443-reserved-tags)
- [`4.5 SKIP Test|Task Status`](website/docs/chapter-04/05_skip.md)
- LO-4.5-1 (K1) Recall the use case and purpose of skipping tests|tasks in Robot Framework
- LO-4.5-2 (K1) Recall the different ways to skip tests|tasks in Robot Framework
- [`4.5.1 Skipping By Tags Selection (CLI)`](website/docs/chapter-04/05_skip.md#451-skipping-by-tags-selection-cli)
  - LO-4.5.1 (K1) Recall the differences between skip and exclude
- [`4.5.2 Skipping Dynamically During Execution`](website/docs/chapter-04/05_skip.md#452-skipping-dynamically-during-execution)
- [`4.5.3 Automatically Skipping Failed Tests`](website/docs/chapter-04/05_skip.md#453-automatically-skipping-failed-tests)
- [`5 Exploring Advanced Constructs`](website/docs/chapter-05/00_overview.md)
- [`5.1 Advanced Variables`](website/docs/chapter-05/01_advanced_variables.md)
- [`5.1.1 Variable Priorities`](website/docs/chapter-05/01_advanced_variables.md#511-variable-priorities)
  - LO-5.1.1 (K2) Understand the difference between statically defined and dynamically created variables in Robot Framework
  - [`5.1.1.1 Statically Defined or Imported Variables`](website/docs/chapter-05/01_advanced_variables.md#5111-statically-defined-or-imported-variables)
    - LO-5.1.1.1 (K1) Recall the priority of statically defined or imported variables in Robot Framework
  - [`5.1.1.2 Dynamically Created Variables`](website/docs/chapter-05/01_advanced_variables.md#5112-dynamically-created-variables)
    - LO-5.1.1.2 (K1) Recall the priority of dynamically created variables in Robot Framework
- [`5.1.2 Variable Scopes`](website/docs/chapter-05/01_advanced_variables.md#512-variable-scopes)
  - LO-5.1.2 (K1) Recall the different variable scopes in Robot Framework
  - [`5.1.2.1 . Global Scope`](website/docs/chapter-05/01_advanced_variables.md#5121--global-scope)
    - LO-5.1.2.1 (K1) Recall how to define global variables and where they can be accessed
  - [`5.1.2.2 . Suite Scope`](website/docs/chapter-05/01_advanced_variables.md#5122--suite-scope)
    - LO-5.1.2.2 (K1) Recall how to define suite variables and where they can be accessed
  - [`5.1.2.3 . Test|Task Scope`](website/docs/chapter-05/01_advanced_variables.md#5123--testtask-scope)
    - LO-5.1.2.3 (K1) Recall how to define test|task variables and where they can be accessed
  - [`5.1.2.4 . Local Scope`](website/docs/chapter-05/01_advanced_variables.md#5124--local-scope)
    - LO-5.1.2.4 (K1) Recall how to define local variables and where they can be accessed
- [`5.1.3 Global Variables via Command Line`](website/docs/chapter-05/01_advanced_variables.md#513-global-variables-via-command-line)
- [`5.1.4 List-Variables (Advanced)`](website/docs/chapter-05/01_advanced_variables.md#514-list-variables-advanced)
  - [`5.1.4.1 Assigning List Variables`](website/docs/chapter-05/01_advanced_variables.md#5141-assigning-list-variables)
    - LO-5.1.4.1 (K1) Recall that assignments to `@{list}` variables convert values to lists automatically
  - [`5.1.4.2 Accessing List Variables`](website/docs/chapter-05/01_advanced_variables.md#5142-accessing-list-variables)
    - LO-5.1.4.2 (K1) Recall that `@{list}` unpacks the values of a list variable when accessed
- [`5.1.5 Dict-Like`](website/docs/chapter-05/01_advanced_variables.md#515-dict-like)
  - [`5.1.5.1 Assigning Dictionary Variables`](website/docs/chapter-05/01_advanced_variables.md#5151-assigning-dictionary-variables)
    - LO-5.1.5.1 (K1) Recall that assignments to `&{dict}` variables automatically convert values to Robot Framework Dictionaries and enable dot-access
  - [`5.1.5.2 Accessing Dictionary Variables`](website/docs/chapter-05/01_advanced_variables.md#5152-accessing-dictionary-variables)
    - LO-5.1.5.2 (K1) Recall that `&{dict}` unpacks to multiple key=value pairs when accessed
- [`5.1.6 Built-In Variables`](website/docs/chapter-05/01_advanced_variables.md#516-built-in-variables)
  - LO-5.1.6 (K1) Recall that Robot Framework provides access to execution information via Built-In variables
- [`5.2 Control Structures`](website/docs/chapter-05/02_control_structures.md)
- [`5.2.1 IF Statements`](website/docs/chapter-05/02_control_structures.md#521-if-statements)
  - LO-5.2.1 (K2) Understand the purpose and basic concept of IF-Statements
  - [`5.2.1.1 Basic IF Syntax`](website/docs/chapter-05/02_control_structures.md#5211-basic-if-syntax)
- [`5.2.2 IF/ELSE IF/ELSE Structure`](website/docs/chapter-05/02_control_structures.md#522-ifelse-ifelse-structure)
- [`5.2.3 Inline IF Statement`](website/docs/chapter-05/02_control_structures.md#523-inline-if-statement)
- [`5.2.4 FOR Loops`](website/docs/chapter-05/02_control_structures.md#524-for-loops)
  - LO-5.2.4 (K2) Understand the purpose and basic concept of FOR Loops
  - [`5.2.4.1 Basic FOR Loop Syntax`](website/docs/chapter-05/02_control_structures.md#5241-basic-for-loop-syntax)
- [`5.2.5 WHILE Loops`](website/docs/chapter-05/02_control_structures.md#525-while-loops)
  - LO-5.2.5 (K2) Understand the purpose and basic concept of WHILE Loops
- [`5.2.6 BREAK and CONTINUE`](website/docs/chapter-05/02_control_structures.md#526-break-and-continue)
  - LO-5.2.6 (K2) Understand the purpose and basic concept of the BREAK and CONTINUE statements
