
# EX.NO.10 – CREATING A CUSTOM GPT FOR SAVEETHA ENGINEERING COLLEGE USING OPENAI'S GPT BUILDER

## AIM

To understand the concept of a Custom GPT and to design, build, configure, test, and publish a Custom GPT chatbot for Saveetha Engineering College using OpenAI's GPT Builder, so that it can answer student and visitor questions about the college's courses, admissions, fees, facilities, placements, and other college-related information.

---

# INTRODUCTION

Artificial Intelligence has evolved from systems designed only for specific calculations into interactive systems capable of communicating with users through natural language.

One important development in this area is the **Custom GPT**.

A Custom GPT is a version of ChatGPT configured for a specific purpose using customized instructions, knowledge files, conversation starters, and selected capabilities. This makes it possible to create a specialized AI assistant without developing a complete conversational AI system from scratch.

For example, instead of using a general-purpose AI assistant to answer questions about a college, an institution can configure a specialized assistant that focuses on information such as:

* Courses
* Admissions
* Eligibility
* Fees
* Departments
* Campus facilities
* Hostel facilities
* Placements
* Contact information
* Frequently asked questions

A Custom GPT can use uploaded knowledge files as reference material and can also be configured with tools such as web search, image generation, data analysis, or external API-based actions, depending on the available configuration and workspace permissions. ([OpenAI Help Center][1])

For this experiment, a conceptual **"Saveetha Engineering College Assistant"** is designed. Its purpose is to provide students and visitors with a convenient way to obtain college-related information.

The development process involves:

**Collect Information → Define Instructions → Configure GPT → Add Knowledge → Enable Capabilities → Test → Publish/Share**

---

# OBJECTIVES

The major objectives of this experiment are:

1. To understand the concept of Custom GPTs.
2. To understand how specialized AI assistants are configured.
3. To collect college-specific information.
4. To prepare knowledge files for the GPT.
5. To create appropriate instructions for the chatbot.
6. To configure the GPT's name and description.
7. To create useful conversation starters.
8. To test the chatbot using sample questions.
9. To understand the role of knowledge and capabilities.
10. To understand how a specialized AI assistant can be used in an educational institution.

---

# WHAT IS A CUSTOM GPT?

A Custom GPT is a customized version of ChatGPT designed for a particular purpose.

A GPT can be configured using several components:

### 1. Instructions

Instructions define how the GPT should behave, what it should do, its tone, and how it should respond.

### 2. Knowledge

Knowledge consists of files uploaded to the GPT that provide reference information.

### 3. Conversation Starters

Conversation starters are example questions displayed to users to help them begin interacting with the GPT.

### 4. Capabilities

Capabilities allow the GPT to use supported features such as web search, image generation, Canvas, or data analysis, depending on availability.

### 5. Actions

Actions allow a GPT to connect to external APIs that are defined by the builder. They can be used when the GPT needs to retrieve information from or interact with an external system. ([OpenAI Help Center][1])

Therefore, a Custom GPT can be represented as:

**Custom GPT = Instructions + Knowledge + Conversation Starters + Selected Capabilities**

---

# PAGE 1 – TOOLS AND REQUIREMENTS

# TOOLS REQUIRED

## 1. Web Browser

A modern web browser such as Google Chrome or Microsoft Edge can be used to access ChatGPT and the GPT editor.

GPT creation and editing are currently performed through the web experience rather than the ChatGPT mobile applications. ([OpenAI Help Center][1])

---

## 2. ChatGPT Account and Workspace

An eligible ChatGPT workspace/account is required to create and publish a new GPT.

**Important current requirement:** OpenAI's current documentation states that new GPT creation and publishing are not available on personal Free, Go, Plus, or Pro accounts. Creation and publishing are available in eligible Business, Enterprise, and Edu workspaces when permitted by workspace settings and user permissions. ([OpenAI Help Center][1])

---

## 3. GPT Builder

The GPT Builder is the environment used to create and configure a GPT.

The builder supports both:

* Conversational building
* Direct configuration

The current GPT editor allows the creator to configure the GPT's name, description, instructions, conversation starters, knowledge, capabilities, and other available settings. ([OpenAI Help Center][1])

---

## 4. College Reference Material

Reliable information about Saveetha Engineering College should be collected from official college sources.

Possible categories include:

* About the institution
* Courses and departments
* Admission information
* Eligibility
* Fee information
* Facilities
* Hostel
* Placements
* Contact information

The official college website should be treated as the primary source for college-specific information.

---

## 5. Document Preparation Software

MS Word or Google Docs can be used to organize information before saving it as PDF or another supported file format.

The information should be organized clearly with headings and tables where appropriate.

---

# PAGE 2 – KNOWLEDGE PREPARATION

# STEP 1: COLLECTING COLLEGE INFORMATION

Before creating the GPT, relevant information about Saveetha Engineering College must be collected.

The purpose of this step is to create reliable reference material that the GPT can use while answering questions.

Information can be organized under headings such as:

### College Overview

Contains:

* Institution name
* General description
* Location
* Institutional information

### Courses

Contains:

* Undergraduate programs
* Postgraduate programs
* Departments
* Course descriptions

### Admissions

Contains:

* Admission procedures
* Eligibility requirements
* Application information
* Important admission instructions

### Fees

Contains:

* Available fee information
* Course-wise information where officially provided
* Instructions for obtaining current fee details

### Facilities

Contains information about:

* Laboratories
* Library
* Hostel
* Sports facilities
* Campus facilities
* Student services

### Placements

Contains:

* Placement information
* Training and placement facilities
* Recruiter information where officially available
* Placement-related procedures

### Contact Information

Contains:

* Official address
* Admission office information
* Official contact channels

---

# PREPARING THE KNOWLEDGE FILE

The collected information should be organized into a clean document.

A suitable structure is:

```text
SAVEETHA ENGINEERING COLLEGE

1. College Overview
2. Courses and Departments
3. Admission Information
4. Eligibility
5. Fee Information
6. Campus Facilities
7. Hostel
8. Placements
9. Contact Information
10. Frequently Asked Questions
```

The document can then be saved in a supported format and uploaded as GPT knowledge.

OpenAI's current documentation recommends using Knowledge for reference material and keeping behavioral rules in the Instructions field. It also recommends clear, text-forward files because complex layouts can make retrieval more difficult. ([OpenAI Help Center][1])

---

# PAGE 3 – CREATING THE GPT

# STEP 2: SIGNING IN TO CHATGPT

The GPT Builder is accessed through ChatGPT's web interface.

The user must sign in using an account belonging to a workspace that permits GPT creation.

The availability of the Create option depends on the account type and workspace permissions.

---

# STEP 3: OPENING THE GPT BUILDER

From the ChatGPT web interface, the user can access the GPTs area and select **Create** if the account has permission to create GPTs.

OpenAI's current instructions describe two ways of building a GPT:

1. **Conversational builder**
2. **Configuration view** ([OpenAI Help Center][1])

The conversational builder allows the creator to describe the desired GPT in natural language.

The configuration view provides more direct control over individual settings.

---

# STEP 4: BUILDING THE GPT CONVERSATIONALLY

In the conversational builder, a description such as the following can be entered:

```text
Create a specialized assistant for Saveetha Engineering College.
The assistant should answer questions about courses, admissions,
eligibility, fees, facilities, placements, and contact information.
It should use the uploaded college knowledge files as its primary
reference and respond in a friendly, professional and concise manner.
```

The builder can then assist with developing the GPT configuration.

The conversational approach is useful for beginners because the creator does not need to manually configure every field initially.

---

# STEP 4A: CONFIGURATION VIEW

After creating the initial version, the configuration settings can be reviewed and refined.

Important fields include:

* Name
* Description
* Instructions
* Conversation starters
* Knowledge
* Capabilities
* Actions, if required

These configuration elements determine how the GPT appears and behaves. ([OpenAI Help Center][1])

---

# PAGE 4 – CONFIGURING THE GPT

# STEP 5: FINE-TUNING WITH THE CONFIGURATION SETTINGS

## NAME

A suitable name can be:

**Saveetha Engineering College Assistant**

The name immediately communicates the purpose of the GPT.

---

## DESCRIPTION

A suitable description is:

**"Your AI guide to courses, admissions, facilities, placements, and other information about Saveetha Engineering College."**

The description should clearly communicate what the GPT does and who it is intended for.

---

# INSTRUCTIONS

Instructions are one of the most important components of a Custom GPT.

They define:

* Role
* Behavior
* Tone
* Response structure
* Information priorities
* Boundaries
* Handling of uncertain information

OpenAI recommends using clear headings and explicit multi-step instructions when defining GPT behavior. ([OpenAI Help Center][1])

---

# SAMPLE INSTRUCTIONS FOR THE GPT

```text
ROLE:
You are the Saveetha Engineering College Assistant.

PURPOSE:
Help students, applicants, parents and visitors obtain useful
information about Saveetha Engineering College.

KNOWLEDGE:
Use the uploaded college knowledge files as the primary source
for college-specific information.

ACCURACY:
Do not invent course details, fees, admission dates, placement
statistics or contact information.

If the required information is not available in the provided
knowledge, clearly state that the information is not available
and direct the user to the appropriate official college source.

TONE:
Be friendly, professional, clear and respectful.

RESPONSE STYLE:
Use headings and bullet points when they improve readability.
Keep simple questions concise.
For complicated questions, provide a structured explanation.

ADMISSIONS:
For admission-related questions, provide only information
supported by the available official reference material.

FEES:
Do not guess or fabricate fee amounts. If current fee information
is unavailable, tell the user to verify the latest official fee
information.

PLACEMENTS:
Present placement information only when supported by the available
college reference material.

OUT-OF-SCOPE QUESTIONS:
If a question is unrelated to the college, politely explain that
the assistant is designed primarily for Saveetha Engineering
College information.

CURRENT INFORMATION:
When an enabled live information capability is appropriate,
use it for information that may have changed since the knowledge
files were prepared.

PRIVACY:
Do not request unnecessary personal information from users.
```

This instruction set separates the GPT's **behavioral rules** from its **reference knowledge**, which is the recommended design approach. ([OpenAI Help Center][1])

---

# PAGE 5 – CONVERSATION STARTERS AND KNOWLEDGE

# STEP 5A: CONVERSATION STARTERS

Conversation starters help users understand what they can ask.

Four suitable examples are:

1. **What courses does Saveetha Engineering College offer?**
2. **How can I apply for admission?**
3. **What facilities are available on campus?**
4. **Where can I find placement information?**

Conversation starters are displayed when users open the GPT and help them begin a useful interaction. ([OpenAI Help Center][1])

---

# STEP 6: UPLOADING KNOWLEDGE FILES

The Knowledge section allows the creator to upload reference files.

The prepared college document can be uploaded here.

The purpose of Knowledge is to provide source material that the GPT can retrieve when answering questions.

Knowledge should contain:

* College information
* Course details
* Admission information
* Facility information
* Placement information
* Contact information

Rules about how the GPT behaves should remain in **Instructions**, rather than being placed only in Knowledge files. ([OpenAI Help Center][1])

OpenAI currently allows up to **20 files per GPT**, with a maximum size of **512 MB per file**, subject to the supported file types and applicable configuration. ([OpenAI Help Center][1])

---

# KNOWLEDGE ORGANIZATION

A well-organized knowledge file could contain:

```text
SAVEETHA ENGINEERING COLLEGE KNOWLEDGE

SECTION 1 – COLLEGE OVERVIEW
SECTION 2 – COURSES
SECTION 3 – DEPARTMENTS
SECTION 4 – ADMISSION
SECTION 5 – ELIGIBILITY
SECTION 6 – FEES
SECTION 7 – FACILITIES
SECTION 8 – HOSTEL
SECTION 9 – PLACEMENTS
SECTION 10 – CONTACT
SECTION 11 – FAQ
```

This makes the information easier to retrieve and maintain.

---

# PAGE 6 – CAPABILITIES AND ACTIONS

# STEP 7: ENABLING CAPABILITIES

Capabilities extend what a GPT can do.

Depending on availability, these can include:

### Web Search

Allows the GPT to retrieve up-to-date information from the web.

This can be useful when college information may have changed after the knowledge files were created.

### Image Generation

Allows the GPT to generate images based on text prompts.

For a college assistant, this is optional.

### Canvas

Can help with drafting, editing, and working with longer structured content.

### Code Interpreter & Data Analysis

Can be used for calculations, data analysis, and charts.

For a basic college information assistant, it is usually not essential.

OpenAI's current documentation lists Web Search, Image Generation, Canvas, Code Interpreter & Data Analysis, and Apps among available capability categories, with availability depending on the account and workspace. ([OpenAI Help Center][1])

For this experiment, **Web Search can be considered useful when current information is required**, while unnecessary capabilities can remain disabled.

---

# STEP 8: SETTING UP ACTIONS

Actions are an advanced feature that allows a GPT to communicate with external APIs.

For example, an institution could theoretically provide an API that supplies:

* Current admission status
* Seat availability
* Current fee notifications
* Event information
* Application status

An action requires API information and an appropriate OpenAPI schema.

OpenAI describes Actions as a way for GPTs to connect to external APIs and notes that authentication and schema configuration are part of the setup. ([OpenAI Help Center][2])

For a beginner-level college information chatbot, Actions are optional and can be omitted.

---

# PAGE 7 – TESTING AND OUTPUT

# STEP 9: TESTING THE GPT

Testing is essential before sharing the Custom GPT.

The Preview environment can be used to test the assistant using realistic questions.

### TEST 1 – COURSES

**User:**

"What courses does Saveetha Engineering College offer?"

**Expected behavior:**

The GPT should provide course information supported by the uploaded knowledge.

---

### TEST 2 – ADMISSION

**User:**

"How can I apply for admission?"

**Expected behavior:**

The GPT should explain the admission process based on the available official information.

---

### TEST 3 – FEES

**User:**

"What is the fee for the course?"

**Expected behavior:**

The GPT should provide the fee only if the information is supported by the knowledge source. It should not invent an amount.

---

### TEST 4 – PLACEMENTS

**User:**

"Tell me about the placement opportunities."

**Expected behavior:**

The GPT should provide relevant placement information available in its knowledge.

---

### TEST 5 – UNKNOWN INFORMATION

**User:**

"What will the admission deadline be five years from now?"

**Expected behavior:**

The GPT should not invent a future date. It should explain that such information cannot be confirmed and direct the user to official sources when appropriate.

---

# TESTING TABLE

| Test | Question                        | Expected Result           |
| ---- | ------------------------------- | ------------------------- |
| 1    | What courses are offered?       | Course information        |
| 2    | How do I apply?                 | Admission information     |
| 3    | What are the fees?              | Available fee information |
| 4    | What facilities are available?  | Facility information      |
| 5    | Tell me about placements        | Placement information     |
| 6    | Where is the college located?   | Location information      |
| 7    | Give me unrelated information   | Politely redirect         |
| 8    | Ask for unavailable information | Clearly state uncertainty |

OpenAI recommends testing the GPT in Preview after adding knowledge and refining instructions based on the results. ([OpenAI Help Center][1])

---

# SAMPLE OUTPUT

```text
User:
What courses does Saveetha Engineering College offer?

Saveetha Engineering College Assistant:

Saveetha Engineering College offers various engineering and
technology programs.

The available programs and departments are listed in the
college's official information provided in my knowledge files.

If you tell me the specific program or department you are
interested in, I can provide the relevant information.
```

---

# SAMPLE ADMISSION CONVERSATION

```text
User:
How can I apply for admission?

Assistant:
The admission process depends on the program and applicable
admission category.

Please refer to the official admission information for the
latest application procedure, eligibility requirements and
important dates.

I can also help you understand the admission information
available in the college knowledge files.
```

The exact factual information displayed by the real GPT should come from the current official source material used for the project.

---

# PAGE 8 – PUBLISHING, RESULT AND CONCLUSION

# STEP 10: PUBLISHING AND SHARING

After testing and correcting the GPT, it can be saved or published according to the available workspace permissions.

Sharing options depend on the account and workspace configuration.

Possible options can include:

* Private/personal access
* Workspace sharing
* Link-based sharing
* Public GPT Store publishing

The exact options available depend on the workspace's settings and permissions. ([OpenAI Help Center][3])

For an educational institution, the GPT could potentially be shared with students and faculty through approved institutional channels.

---

# OUTPUT

A working Custom GPT named:

**"Saveetha Engineering College Assistant"**

is configured with:

* A college-specific name
* A descriptive purpose
* Detailed instructions
* Conversation starters
* College knowledge files
* Appropriate capabilities

The GPT can answer questions related to:

* Courses
* Admissions
* Eligibility
* Fees
* Facilities
* Placements
* Contact information

The quality of the responses depends on the accuracy and completeness of the knowledge files and instructions.

---

# RESULT

Thus, a Custom GPT chatbot for **Saveetha Engineering College** was successfully designed as a specialized AI assistant using GPT configuration concepts.

The GPT was configured with appropriate instructions, conversation starters, knowledge resources, and selected capabilities. It was tested using sample student and visitor questions to evaluate its accuracy, relevance, and response style.

---

# ADVANTAGES

## 1. No Traditional Programming Required

A Custom GPT can be configured using natural-language instructions rather than requiring the developer to build a complete chatbot application from scratch.

## 2. Specialized Knowledge

The GPT can use uploaded college-specific reference files.

## 3. Easy Interaction

Students can ask questions using natural language.

## 4. Consistent Behavior

Instructions can define how the assistant should respond.

## 5. Expandable

Additional knowledge files and appropriate capabilities can be added when required.

## 6. Useful for Student Support

A specialized assistant can help users find information quickly.

---

# LIMITATIONS

## 1. Information Can Become Outdated

College information such as fees, admission dates, courses, and placement details can change.

Therefore, knowledge files must be reviewed and updated periodically.

## 2. AI Responses Require Verification

A Custom GPT should not be treated as an unquestionable source of official information.

Important admission, financial, or administrative decisions should be verified through official college sources.

## 3. Workspace Restrictions

Creation and publishing depend on account type and workspace permissions. OpenAI's current policy does not allow new GPT creation on personal Free, Go, Plus, or Pro accounts. ([OpenAI Help Center][1])

## 4. Static Knowledge Has Limits

Uploaded files provide reference material but do not automatically guarantee that every future change to college information will be reflected.

## 5. External Systems Require Additional Setup

Features such as live application-status checking would require suitable external integrations or APIs.

---

# FUTURE ENHANCEMENTS

The college assistant could be developed further by integrating:

### 1. Real-Time College Information

Connect approved sources so that frequently changing information can be updated more easily.

### 2. Admission API

An authorized API could provide current application and admission information.

### 3. Multilingual Support

The assistant could support commonly used languages to improve accessibility.

### 4. Student Services

The system could potentially assist with general student-service information.

### 5. Department-Specific Assistants

Separate specialized assistants could be created for:

* Admissions
* Placements
* Departments
* Student services
* Campus facilities

### 6. Advanced API Integration

Authorized external APIs could allow the GPT to retrieve information from institutional systems through Actions. ([OpenAI Help Center][2])

---

# CONCLUSION

In conclusion, creating a Custom GPT demonstrates how modern generative AI systems can be configured into specialized assistants for particular organizations and purposes.

Instead of developing a complete chatbot application from the beginning, a Custom GPT can be configured using **instructions, knowledge files, conversation starters, and selected capabilities**.

For Saveetha Engineering College, such an assistant can serve as an information-support system for students, applicants, parents, faculty, and visitors. It can provide organized responses about courses, admissions, facilities, placements, and other college-related topics.

The experiment also demonstrates an important principle of modern AI system design: **good AI performance depends not only on the underlying model but also on the quality of the instructions, reference information, testing process, and tools provided to the system.**

A well-designed college assistant should use reliable and current information, avoid inventing facts, clearly communicate uncertainty, and direct users to official college sources for information that requires confirmation.

Therefore, the experiment provides a practical introduction to **Custom GPT development and configuration** and demonstrates how generative AI can be adapted to support educational institutions without requiring the development of a traditional chatbot from scratch.

---

## FINAL SUMMARY

The main components of the Saveetha Engineering College Custom GPT are:

**Name:** Saveetha Engineering College Assistant

**Purpose:** Answer college-related questions

**Instructions:** Define role, behavior, tone, accuracy, and boundaries

**Knowledge:** Official college reference material

**Conversation Starters:** Common student questions

**Capabilities:** Selected according to the required functionality

**Testing:** Preview using realistic student questions

**Publishing:** Share according to available workspace permissions

**Overall Workflow:**

**Collect Information → Prepare Knowledge → Configure GPT → Add Instructions → Add Capabilities → Test → Share/Publish**

