# HealthBot
**HealthBot** is a console based chatbot application which assists a ***clinical person*** to ease the purchase of available ***patient monitoring devices*** that are relevant to him.   
***ChatBot*** asks a set of multiple-choice questions to clinical person and based on his choices, a small set of suitable patient monitors are suggested to him. Questions are formed based on various features of different patient monitors.  

### Important Features of ChatBot:
1. **Display Patient Monitors:** User can view a set of filtered patient monitors based on his previous choices at any stage during the conversation.
2. **Go Back:** User can go back to the previous question at any stage during the conversation.
3. **Start Again:** User can start the conversation from the beginning at any stage.
4. **Abort:** User can end the conversation at any stage.

A **patient monitor** is an electronic medical device that consists of one of more monitoring sensors, a processing component(s), and a screen display(also called a "monitor") that provide and record for medical professionals a patient's medical vital signs(body temperature, blood pressure, pulse rate and respiratory rate) or measurements of the activity of various body organs such as ECG monitors, anesthesia monitors, or EKG monitors.

## UML Class Diagram:
**UML class diagram** for HealthBot application.
![HealthBot UML Class Diagram](https://github.com/anuprshetty/HealthBot/blob/master/images/HealthBotUMLClassDiagram.png)

## Database Model:
**Database model** for HealthBot application.
![HealthBot Database_Model](https://github.com/anuprshetty/HealthBot/blob/master/images/DBSchema_to_DBObject.png)

## Tools and Technologies Used:
- Visual Studio
- C# (.NET Framework)
- Microsoft SQL Server Express Edition
- Microsoft SQL Server Management Studio
- Batch programming
- Git

## Project Setup:
### Database Setup:
- Install Microsoft SQL Server and Microsoft SQL Server Management Studio.
- Open Microsoft SQL Server Management Studio.
- Import and execute **HealthBot.sql** file in Microsoft SQL Server Management Studio.
- View **ChatbotDB** database.

### Code Setup:
- Install Microsoft Visual Studio to work with .NET desktop development.
- Open C# solution **HealthBot.sln** in Microsoft Visual Studio.
- Install all the built-in packages required for C# solution using Microsoft Visual Studio.
- Establish a connectivity to database server using **Server Explorer** in Microsoft Visual Studio.
- Run the batch file **AutoBuildRun.bat** to chat with **HealthBot**.

## References:
- [Philips Patient Monitors](https://www.philips.co.in/healthcare/solutions/patient-monitoring/patient-monitoring)

## Author Info:
- [LinkedIn](https://www.linkedin.com/in/anuprshetty/)
- [HackerRank](https://www.hackerrank.com/anuprshetty)

[Back To The Top](#HealthBot)
