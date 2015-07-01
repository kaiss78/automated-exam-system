# Building the Right System #

Automated exam system.

## 1.0 Admin create/edit user use case ##
**1.1 Use case description:**| **Use case number** | 1 |
|:--------------------|:--|
| **use case name**   | Admin create/edit user|
| **Actors**          | System Administrator|
| **Brief Description** | This use case describes the way of Administrator  to create or edit ESL's instructors. |
| **Precondition**    | Administrator must have to log in into the system|
| **Basic Flow**      | Administrator creates or edit the information of ESL's instructors. |
| **Post-condition**  | System will generate a confirmation message about ESL's instructors database update. |

**Table 1.2 Scenario for Admin create/edit user:**

| **Basic Flow** | **Description**|
|:---------------|:---------------|
| B1             | Administrator  enter user name and password |
| B2             | Validate System Administrator is performed. |
| B3             | The system display the main window that has different choice that the Administrator need. In this case the Administrator select "create/edit user". |
| B4             | The system display another window for create user |
| B5             | The Administrator select the school. |
| B6             | The Administrator add or update the ESL's instructors information such as(username,password,and privileges). |
| B7             | The Administrator select save. |
| B8             | The system show massage of confirmation. |
| B9             |The Administrator  log out. |


**Table 1.3 Scenario for Admin create/edit user(Alternative Flow):**

| **Alternative Flow** | **Description**|
|:---------------------|:---------------|
| A1                   | If in step 2 does not complete successfully, then ends with a failure condition. |
| A2                   | If step 6 exist, then system show massage that user exist. |

**1.4 Use Case Flow Scenarios:**

![https://scontent-b-ord.xx.fbcdn.net/hphotos-prn2/1488295_660561773965953_2126990884_n.jpg](https://scontent-b-ord.xx.fbcdn.net/hphotos-prn2/1488295_660561773965953_2126990884_n.jpg)

**1.5 All Scenarios:**

| **Scenarios number** | **Originating flow** | **Alternative Flow** |
|:---------------------|:---------------------|:---------------------|
| 1                    | Basic Flow           |                      |
| 2                    | Basic Flow           | A1                   |
| 3                    | Basic Flow           | A2                   |

**1.6 Variables Identified:**

| **Step** | **Variable** | **Options to be tested** |
|:---------|:-------------|:-------------------------|
| 1        | Log in       | empty username/ password, Wrong username/ password, Valid username/ password |
| 2        | add /update ESL's instructors information| User exist, system confirm |

**1.7 Test Paths**

| **Step** | **Variable** | **Value** | **Expected Result** | **Pass/Fail** |
|:---------|:-------------|:----------|:--------------------|:--------------|
| 1        | Log in       | Valid username/ password | Enter to the system | Pass          |
| 2        | add /update ESL's instructors information | Enter instructor's information | system confirm      | Pass          |

## 2.0 Maintain Questions bank use case ##
**2.1 Use case description:**| **Use case number** | 2 |
|:--------------------|:--|
| **use case name**   | Maintain Questions bank |
| **Actors**          | ESL's Instructors|
| **Brief Description** | This use case describes the way to maintain questions bank. |
| **Precondition**    | ESL's Instructors must have to log in into the system|
| **Basic Flow**      | ESL's Instructors maintain the questions bank. |
| **Post-condition**  | System will generate a confirmation message about questions bank's database update. |

**Table 2.2 Scenario for Maintain Questions bank:**

| **Basic Flow** | **Description**|
|:---------------|:---------------|
| B1             | ESL's Instructors enter user name and password |
| B2             | Validate System Administrator is performed. |
| B3             | The system display the main window that has different choice that the ESL's Instructors need. In this case the ESL's Instructors select "Maintain Questions bank". |
| B4             | The system display another window for Maintain Questions bank |
| B5             | The ESL's Instructors add/select the subject. |
| B6             | The ESL's Instructors add/select the chapter. |
| B7             | The ESL's Instructors add or update questions with their solutions and difficulty. |
| B8             | The ESL's Instructors select save. |
| B9             | The system show massage of confirmation. |
| B10            |The ESL's Instructors log out. |


**Table 2.3 Scenario for Maintain Questions bank(Alternative Flow):**

| **Alternative Flow** | **Description**|
|:---------------------|:---------------|
| A1                   | If in step 2 does not complete successfully, then ends with a failure condition. |
| A2                   | If step 4 does not exist, then ESL's Instructors do not have the authority to maintain questions. |

**2.4 Use Case Flow Scenarios:**

![https://scontent-b-ord.xx.fbcdn.net/hphotos-ash3/1476263_660561777299286_1550288023_n.jpg](https://scontent-b-ord.xx.fbcdn.net/hphotos-ash3/1476263_660561777299286_1550288023_n.jpg)

**2.5 All Scenarios:**

| **Scenarios number** | **Originating flow**| **Alternative Flow**|
|:---------------------|:--------------------|:--------------------|
| 1                    | Basic Flow          |                     |
| 2                    | Basic Flow          | A1                  |
| 3                    | Basic Flow          | A2                  |

**2.6 Variables Identified:**

| **Step** | **Variable** | **Options to be tested** |
|:---------|:-------------|:-------------------------|
| 1        | Log in       | empty username/ password, Wrong username/ password, Valid username/ password |
| 2        | Maintain Questions bank | user don't have the authority, system confirm |

**2.7 Test Paths**

| **Step** | **Variable** | **Value** | **Expected Result** | **Pass/Fail** |
|:---------|:-------------|:----------|:--------------------|:--------------|
| 1        | Log in       | Valid username/ password | Enter to the system | Pass          |
| 2        | Maintain Questions bank | Add or update questions | system confirm      | Pass          |

## 3.0 Generate exam use case ##
**3.1 Use case description:**| **Use case number** | 3 |
|:--------------------|:--|
| **use case name**   | Generate exam|
| **Actors**          | ESL's Instructors |
| **Brief Description** | This use case describes the way to generate exams for students on specific subjects, chapters and different questions level. |
| **Precondition**    | ESL's Instructors must have to log in into the system|
| **Basic Flow**      | Users write the information for the exam then print the paper|
| **Post-condition**  | System will generate a confirmation message about database update|

**Table 3.2 Scenario for Generate exam.**

| **Basic Flow** | **Description**|
|:---------------|:---------------|
| B1             | ESL's instructors enter user name and password |
| B2             | Validate ESL's instructors/ System Administrator is performed. |
| B3             | The system display the main window that has different choice that the user need. In this case the ESL's instructors select "managing exam". |
| B4             | The system display another window for managing exam |
| B5             | The ESL's instructors select the subject. |
| B6             | The ESL's instructors select the chapter |
| B7             | The ESL's instructors select the number of questions, and difficultly of question. |
| B8             | The ESL's instructors add the information of the exam such as location of exam, date of exam, time of exam, and type of exam. |
| B9             | The ESL's instructors select apply. |
| B10            | The system show form of exam with solution. |
| B11            | The ESL's instructors can print the exam and save it. |
| B12            |The ESL's instructors log out. |


**Table 3.3 Scenario for Generate exam(Alternative Flow).**

| **Alternative Flow** | **Description**|
|:---------------------|:---------------|
| A1                   | If in step 2 does not complete successfully, then ends with a failure condition. |
| A2                   | If step 5 does not exist, then ESL's instructors need to create  subject questions bank first to complete this use case. |
| A3                   | If step 6 does not exist, then ESL's instructors need to create chapter in questions bank first to complete this use case. |
| A4                   | If step 7 does not exist, then ESL's instructors need to create more questions in questions bank first to complete this use case. |

**3.4 Use Case Flow Scenarios:**

![https://scontent-b-ord.xx.fbcdn.net/hphotos-frc1/1002636_660561787299285_709175210_n.jpg](https://scontent-b-ord.xx.fbcdn.net/hphotos-frc1/1002636_660561787299285_709175210_n.jpg)

**3.5 All Scenarios:**| **Scenarios number** | **Originating flow**| **Alternative Flow**|
|:---------------------|:--------------------|:--------------------|
| 1                    | Basic Flow          |                     |
| 2                    | Basic Flow          | A1                  |
| 3                    | Basic Flow          | A2                  |
| 3                    | Basic Flow          | A3                  |
| 3                    | Basic Flow          | A4                  |

**3.6 Test cases for generating exam with identified condition:**| **Test case id** | **Scenario** | **Description** | **Condition** | **Excepted result** |
|:-----------------|:-------------|:----------------|:--------------|:--------------------|
| 1                | 1            | Basic flow:Instructor log in to the system | Invalid input | empty user name or pass, wrong user name or pass |
| 2                | 2            | Alternate flow:The ESL's instructors select the subject. | Invalid: Subject is not add | instructors need to create subject questions bank first to complete this use case |
| 3                | 3            | Alternate flow:The ESL's instructors select the chapter | Invalid:Chapters are not add | ESL's instructors need to create chapter in questions bank first to complete this use case. |
| 4                | 4            | Alternate flow:The ESL's instructors select the number of questions, and difficultly of question | Invalid:Questions are not add or enough | ESL's instructors need to create more questions in questions bank first to complete this use case. |

**3.6 Variables Identified:**

| **Step** | **Variable** | **Options to be tested** |
|:---------|:-------------|:-------------------------|
| 1        | Log in       | empty username/ password, Wrong username/ password, Valid username/ password |
| 2        | Select subject| Subject isn't add, Subject is available|
| 3        | Select chapter | chapter isn't add, chapter is available|
| 4        | Select number of questions and difficultly of question | number/ difficultly of questions aren't add, number/ difficultly of questions are add |

**3.7 Test Paths**

| **Step** | **Variable** | **Value** | **Expected Result** | **Pass/Fail** |
|:---------|:-------------|:----------|:--------------------|:--------------|
| 1        | Log in       | Valid username/ password | Enter to the system | Pass          |
| 2        | Select subject| Subject is available | System asks to add chapters | Pass          |
| 3        | Select chapter | chapter is available | System asks to add number & difficultly of questions | Pass          |
| 4        | Select number/difficultly of question | number/ difficultly of questions are add | choose number/ difficultly of questions | Pass          |

## 4.0 View statistics questions use case ##
**4.1 Use case description:**| **Use case number** | 4 |
|:--------------------|:--|
| **use case name**   | View statistics questions|
| **Actors**          | ESL's Instructors and System Administrator|
| **Brief Description** | Allow to ESL's instructors to view statistics questions|
| **Precondition**    | ESL's Instructors/ Administrator must have to log in into the system|
| **Basic Flow**      | Select the subject in which you have to view Statistics for questions|
| **Post-condition**  | The system will view Statistical reports |

**4.2  Scenario for statistics questions.**

| **Basic Flow** | **Description**|
|:---------------|:---------------|
| B1             | ESL's instructors/ System Administrator enter user name and password |
| B2             | Validate ESL's instructors/ System Administrator is performed. |
| B3             | The system display the main window that has different choice that the user need. In this case the ESL's instructors/ System Administrator select "statistics questions". |
| B4             | The ESL's instructors/ System Administrator select the course. |
| B5             | The ESL's instructors/ System Administrator select apply. |
| B6             | The system view Statistical reports. |
| B7             | The ESL's instructors/ System Administrator can print statistical reports. |
| B8             |The ESL's instructors/ System Administrator log out. |


**4.3 Scenario for statistics questions(Alternative Flow).**

| **Alternative Flow** | **Description**|
|:---------------------|:---------------|
| A1                   | If in step 2 does not complete successfully, then ends with a failure condition. |
| A2                   | If step 4 does not exist, then ESL's instructors/ System Administrator need to create questions bank for the course to complete this use case. |

**4.4 Use Case Flow Scenarios**

![https://googledrive.com/host/0B4l_YtJunMYOV2VqaHluWnRuOXM/Screen_Shot_2013-12-02_at_4.jpg](https://googledrive.com/host/0B4l_YtJunMYOV2VqaHluWnRuOXM/Screen_Shot_2013-12-02_at_4.jpg)

**4.5 All Scenarios**

| **Scenarios number** | **Originating flow**| **Alternative Flow**|
|:---------------------|:--------------------|:--------------------|
| 1                    | Basic Flow          |                     |
| 2                    | Basic Flow          | A1                  |
| 3                    | Basic Flow          | A2                  |

**4.6 Variables Identified:**

| **Step** | **Variable** | **Options to be tested** |
|:---------|:-------------|:-------------------------|
| 1        | Log in       | empty username/ password, Wrong username/ password, Valid username/ password |
| 2        | course       | ESL instructor/ System Administrator need to create questions bank, system confirm |

**4.7 Test Paths**

| **Step** | **Variable** | **Value** | **Expected Result** | **Pass/Fail** |
|:---------|:-------------|:----------|:--------------------|:--------------|
| 1        | Log in       | Valid username/ password | Enter to the system | Pass          |
| 2        | course       | Choose course | system confirm      | Pass          |