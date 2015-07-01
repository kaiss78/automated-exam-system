# Defining the System #
## 1. Introduction ##
> ### 1.1 Purpose of the Vision Document ###
> > The Document will include requirement collection, analyze, describe User needs and project highlights for Generated Exam System.


> ### 1.2 Product Overview ###
> > This Generated Exam System would provides an easy and efficient way to generate different forms of exams for ESL's instructors. It makes a database of questions depending on class subjects, chapters, question types (multiple choice or true/false) and the difficulty level of questions (easy– medium– hard).


> ### 1.3 References ###
> > [ProjectProposal](ProjectProposal.md)
> > [TeamSkill1](TeamSkill1.md)
> > [TeamSkill2](TeamSkill2.md)

## 2. User Description ##

> ### 2.1 User/Market Demographics ###
> > ESL's Instructors are the main users for the system.

> ### 2.2 User Profiles ###
> > ESL's instructors: To access and update database of questions


> ### 2.3 User Environment ###
> > This system can support any of the windows based Operating System. It has complete web-based solution provides easy user interface.

> ### 2.4 Key User Needs ###
    * **ESL's Instructor perspective:**
      * Generate more than one form of the exam.
      * Generate exam without repetition of questions.
      * Make different kind of question.
      * Take short time to make the exam.
      * Allow to define difficulties of questions.
      * Allow to define numbers of questions.
      * Easy to use and make format of exam.
      * Access anywhere and anytime.
      * Make the solution of the exam in the same time.
      * Update the bank of questions anytime.

  * **student Benefits:**
    * The possibility of taking the exam in the same exam's day.
    * Cover the materials of course equally.
    * The diversity of questions.
> ### 2.5 Alternatives and Competition ###
> > As of right now, there is no such other product on the market that competes directly with this product.

## 3. Product Overview ##

> ### 3.1 Product Perspective ###
    * Instructors will use the website to generate exam.
    * System will connect to the database to generate exam.
    * System will print questions and answers papers.

![https://googledrive.com/host/0B4l_YtJunMYOV2VqaHluWnRuOXM/Screen_Shot_.jpg](https://googledrive.com/host/0B4l_YtJunMYOV2VqaHluWnRuOXM/Screen_Shot_.jpg)

> ### 3.2 System Position Statement ###
| **For** | Academic/Education institute |
|:--------|:-----------------------------|
| **Who** | ESL's instructors            |
| **Automated Exam System** | Is a system to generate different models of exams |
| **That** | Allow to get easy and fast way to generate exam |
| **Unlike** | Any other traditional way to create exam like Microsoft Word |
| **Our product** | Generate an exam through a website online |

> ### 3.3 Summary of Capabilities ###

| **customer benefit** | **Supporting features** |
|:---------------------|:------------------------|
| Ability to define privileges for user | database administrator can define privileges like identification, authorization and authentication |
| Ability to add questions in database | privilege to access & maintain database |
| Ability to define difficulties of questions  | Users can identify difficulty level of questions (easy – medium –hard) |
| Ability to generate many exams  | create numerous exams in different classes |
| Ability to organize exams paper format | privilege to change exam’s paper format such as logo or any specific information |

> ### 3.4 Assumptions and Dependencies ###
> > The following assumptions and dependencies are related to the Generate Exam System:
      * ESL institute has a website.
      * Oracle Database must be preinstalled.
      * Users have a computer (either desktop or laptop) to access the web interface.
      * The internet access should be available.


> ### 3.5 Cost and Pricing ###
> > The cost of the system will be determined later due to awaiting software development and marketing costs as well as the cost of maintaining an online database to store all information.

## 4. Feature Attributes ##
| **Function** | **Status** | **Priority** | **Effort** | **Risk** | **Stability** |
|:-------------|:-----------|:-------------|:-----------|:---------|:--------------|
|Generate exam without repetition of questions|Approved    |Critical      |High        |High      |High           |
|Maintain questions bank|Approved    |Important     |High        |High      |High           |
|Easy to administrate the system|Approved    | Critical     |Medium      | High     | Medium        |
|Statistics for questions|Approved    |Critical      |High        |High      |High           |
|short time to generate exam|Approved    |Important     |High        |High      |Medium         |
|Different access for instructors and administrator|Approved    |Important     |High        |High      |High           |
|the exam questions have solutions' copy|Approved    |Important     |High        |Low       |Medium         |
|multiple choice maker or true/false format|Approved    |Important     |High        |High      |High           |
|The system has ability to work on any OS environment|Approved    |Critical      |High        |High      |High           |
|Flexibility to organize the form of the exam|Approved    |Important     |Medium      |Low       |Medium         |
| Allow to define difficulties of questions| Approved   | Important    | Medium     | Low      | Medium        |
|provides full  word processing capabilities including font selections, size and other attributes|Approved    |Useful        | Medium     | Medium   | High          |
|Able to add new features in the future|Approved    | Important    | Medium     | Low      | Low           |

## 5. Automated Exam system Features ##

> ### 5.1 Critical Feature ###
    * Generate exam without repetition of questions: To generate the random test paper without repetition of same question is very important feature of the system. As a test shouldn't have the same question repeated again
    * Secure Database: Users can access only to particular database that assigned to them. Also the questions' bank of particular subject has to protect to the unauthorized access
    * Ability to support any OS environment : The software will support any OS environment Windows, Mac, and Linux

> ### 5.2 Important Feature ###
    * Flexibility to organize the form of the exam: privilege to change exam’s paper format such as logo or other specific information
    * Allow to define difficulties of questions: Users have ability to define difficulties of questions ( Easy- Medium- Hard)
    * Exam questions have solutions' copy: when users print the exam, system will be automatically print solutions' copy

## 6. Exemplary Use Case ##
> ### 6.1 Use Cases ###
![https://googledrive.com/host/0B4l_YtJunMYOV2VqaHluWnRuOXM/usecase-lastone-2.jpg](https://googledrive.com/host/0B4l_YtJunMYOV2VqaHluWnRuOXM/usecase-lastone-2.jpg)
> ### 6.2 Use cases Description ###

> 6.2.1 Create new user use case
| **use case name** | Create new user|
|:------------------|:---------------|
| **Actors**        | System Administrator|
| **Brief Description** | To create a new username and password to instructors|
| **Precondition**  | Administrator must have to log in into the system|
| **Basic Flow**    | The use case begins with customer information entered by the administrator to register new membership for instructors|
| **Post-condition** | After the registration is successful, the system must have all details about the user and users can use the system|

> 6.2.2 Edit/ Delete user use case
| **use case name** | Edit/ Delete user|
|:------------------|:-----------------|
| **Actors**        | System Administrator|
| **Brief Description** | To modify or delete a instructor information|
| **Precondition**  | Administrator must have to log in into the system|
| **Basic Flow**    | Administrator will modify or delete instructors' data|
| **Post-condition** | The system will update instructor's information in database|

> 6.2.3 Maintain new subject use case
| **use case name** | Maintain new subject |
|:------------------|:---------------------|
| **Actors**        | Instructors and System Administrator|
| **Brief Description** | To create a new subject in database|
| **Precondition**  | Instructors/ Administrator must have to log in into the system|
| **Basic Flow**    | Create a new subject which you have to upload your chapters then database will save it automatically|
| **Post-condition** | System will generate a confirmation message about database update|

> 6.2.4 Maintain new chapter use case
| **use case name** | Maintain new chapter|
|:------------------|:--------------------|
| **Actors**        | Instructors and System Administrator|
| **Brief Description** | To create a new chapters in database for each subject|
| **Precondition**  | Instructors/ Administrator must have to log in into the system and add a new subject|
| **Basic Flow**    | Create a new chapters for each subjects that you already created before then database will save it automatically|
| **Post-condition** | System will generate a confirmation message about database update|

> 6.2.5 Maintain new questions use case
| **use case name** | Maintain new question|
|:------------------|:---------------------|
| **Actors**        | Instructors and System Administrator|
| **Brief Description** | To add questions in database for each chapter|
| **Precondition**  | Instructors/ Administrator must have to log in into the system and added a subject and chapter|
| **Basic Flow**    | Select the subject in which they have to upload their questions then Write questions and submit them. Database will save it automatically|
| **Post-condition** | System will generate a confirmation message about database update|

> 6.2.6 Generate exam use case
| **use case name** | Generate exam|
|:------------------|:-------------|
| **Actors**        | Instructors and System Administrator|
| **Brief Description** | To add exam information such as (instructor name - exam type - duration - date - class name)|
| **Precondition**  | Instructors/ Administrator must have to log in into the system|
| **Basic Flow**    | Users write the information for the exam then print the paper|
| **Post-condition** | System will generate a confirmation message about database update|

> 6.2.7 Print exam/ solution use case
| **use case name** | Print exam/ solution|
|:------------------|:--------------------|
| **Actors**        | Instructors and System Administrator|
| **Brief Description** |To get two copies of exam (paper questions and answers’ paper)|
| **Precondition**  | Instructors/ Administrator must have to log in into the system|
| **Basic Flow**    |After generate exam you will get two hardcopies and they can print exam’s paper questions and answers’ paper|
| **Post-condition** | N/A                 |

> 6.2.8 View statistics questions use case
| **use case name** | View statistics questions|
|:------------------|:-------------------------|
| **Actors**        | Instructors and System Administrator|
| **Brief Description** | Allow to instructors to view statistics questions|
| **Precondition**  | Instructors/ Administrator must have to log in into the system|
| **Basic Flow**    | Select the subject in which you have to view Statistics for questions|
| **Post-condition** | The system will view Statistical reports|

## 7. Other Product Requirements ##
> ### 7.1 Applicable Standards ###
    * Internet access
    * UL, CMM, ISO for safety and quality standards
    * Windows for platform compliance standards
> ### 7.2 System Requirements ###
    * Oracle database must be preinstalled
    * Web server : SUN JAVA system web server 7.0 with JDBC oracle connectivity
    * 1GB RAM, 160 GB Hard disk space
> ### 7.3 Licensing, Security, and Installation ###
    * There should be some terms and conditions set forth the rights being licensed to the customer for use of this system. , so if customer does not agree to the terms and conditions, then they cannot use it.
    * users will have to create a user ID and password, which will be have a limited life.
    * There should be some terms and conditions set forth the rights being licensed to the customer for use of this system. , so if customer does not agree to the terms and conditions, then they cannot use it.
## 8. Documentation Requirements ##
> ### 8.1 User Manual ###
> > The user manual provides the instructions to use the system and maintain the system. Each user gets their own documentation by hard copy.

> ### 8.2 Online Help ###
> > via Frequently Asked Questions (FAQ)

> ### 8.3 Installation Guides, Configuration, Read Me File ###
> > Automated Exam system supposes to be easy for customer to use

> ### 8.4 Labeling and Packaging ###
> > All terms and licenses have to be signed before the system launched.
## 9. Glossary ##