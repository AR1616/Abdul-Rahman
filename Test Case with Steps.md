# Monefy APP Test Cases: 
---
### TestCase ID - 1

##### Type &emsp; : Functional
##### Priority : High
##### Test Case Description:
Verify that application should be Installed successfully.
##### Pre-Condition:
User has downloaded the application successfully. 

##### Steps:
1. Open the APK

##### Expected result:
Monefy application should get installed and opened successfully.
##### Actual Result: 
Monefy application installed successfully.
##### Status: Pass
---
### TestCase ID - 2

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify that when user switch from light to dark mode or vice versa, and then tap on cross icon on "Become your own budgeting hero" guide card, then application should redirect user onto home screen. 
##### Pre-Condition:
User has opened the application for the first time. 

##### Steps:
1. Open the application
2. Swipe the application to the last guide card "Become your own budgeting hero"
3. switch from light mode to dark mode
4. tap on cross icon button

##### Expected result:
Application should redirect user onto home screen.
##### Actual Result: 
Application remain on "Become your own budgeting hero" guide card.
##### Status: Fail
---
### TestCase ID - 3

##### Type &emsp; : Functional
##### Priority : low
##### Test Case Description:
Verify that when the user switches from light to dark mode or vice versa on the home screen, then the application should remain the user on the home screen. .
##### Pre-Condition:
user has installed and opened app 

##### Steps:
1. Open application
2. Upon dashboard, switch from light mode to dark mode

##### Expected result:
Application should remain user onto home screen.
##### Actual Result: 
Application gets redirects to guide card.
##### Status: Fail
---
### TestCase ID - 4

##### Type &emsp; : Non- Functional
##### Priority : low
##### Test Case Description:
Verify that the Mobile Application home screen should display the proper bold header. 
##### Pre-Condition:
user has installed and opened app 

##### Steps:
1. Open application
2. Upon dashboard/home screen

##### Expected result:
Mobile Application home screen should display the proper bold header.
##### Actual Result: 
small header is currently displayed.
##### Status: Fail
---
### TestCase ID - 5

##### Type &emsp; : Non- Functional
##### Priority : Medium
##### Test Case Description:
Verify that App Logo should be displayed in the middle of the header and under that logo the current selected account space should be displayed
##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. Open application
2. Upon dashboard/home screen

##### Expected result:
App Logo should be displayed in the middle of the header and under that logo the current selected account space should be displayed.
##### Actual Result: 
Currently App Logo is being displayed on left side.
##### Status: Fail
---
### TestCase ID - 6

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify that when the app is open for the first time, then the app should auto-select the currency of that country in which the customer is currently residing. If that country's currency is not available in the list then the application should ask the customer for the currency selection. 

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. Open application
2. Upon dashboard/home screen

##### Expected result:
app should auto-select the currency of that country in which the customer is currently residing. If that country's currency is not available in the list then the application should ask the customer for the currency selection.
##### Actual Result: 
GBP (pound) currency is currently being auto selected as default currency.
##### Status: Fail
---
### TestCase ID - 7

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify that on selecting the "Menu" icon option from the top left side of the header bar , user should be able to see left-side menu.
##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. Open application
2. Upon dashboard/home screen, tap on top-left menu icon

##### Expected result:
user should be able to see left-side menu.
##### Actual Result: 
user is being able to see left-side menu..
##### Status: Pass
---
### TestCase ID - 8

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify that on selecting the "Menu" icon option from the top left side of the header bar, the user should be able to see the left-side menu. And right after, if the user selects any other option from the top header of the home screen then the side menu should get closed automatically and the currently selected option should get opened.
##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. Open application
2. Upon dashboard/home screen, tap on top-left menu icon
3. tap on search or transfer icon

##### Expected result:
The left side menu should get closed automatically and the currently selected option should get opened.
##### Actual Result: 
After the opening of the left-side menu, upon selecting the (search or transfer) icon, in both cases, the left-side menu doesn’t get closed.
##### Status: Fail
---
### TestCase ID - 9

##### Type &emsp; : non -Functional
##### Priority : low
##### Test Case Description:
Verify that upon searching prolong the length of text in the "search record", then the search record history should display the complete content of the already searched transaction.

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. Open application
2. Upon dashboard/home screen, tap on search icon from header
3. enter any prolong text and proceed for search
4. after that again enter text in search bar

##### Expected result:
The search record history should display the complete content of the already searched transaction
##### Actual Result: 
The search record history displays half cut content of the already searched transaction.
##### Status: Fail
---
### TestCase ID - 10

##### Type &emsp; : non -Functional
##### Priority : low
##### Test Case Description:
Verify that upon searching prolong the length of text in the "search record", then the search record history should display the complete content of the already searched transaction.

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. Open application
2. Upon dashboard/home screen, tap on search icon from header
3. enter any prolong text and proceed for search
4. after that again enter text in search bar

##### Expected result:
The search record history should display the complete content of the already searched transaction
##### Actual Result: 
The search record history displays half cut content of the already searched transaction.
##### Status: Fail
---

### TestCase ID - 11

##### Type &emsp; : non -Functional
##### Priority : low
##### Test Case Description:
Verify splash screen.

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. Open application

##### Expected result:
Splash screen should appear before opening of main dashboard/home screen.
##### Actual Result: 
Currently guide card gets open every time and if user has subscribed to full feature then application directly opens main dashboard.
##### Status: Fail
---

### TestCase ID - 12

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the selection of day/week/month/year/All/Interval/Choose date

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. tap on left side menu button from header bar
2. select day or week or month or year or All or Interval or Choose date

##### Expected result:
1. upon selection of any future date
     app should not allow the user to select any future date with respect to current date.
2. upon selection of any past date
     app should not allow the user to select any older date before the year 1970.
##### Actual Result: 
Currently, application is allowing to select future date upto year 2099 and older date upto year 1900.
##### Status: Fail
---
### TestCase ID - 13

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the selection of day/week/month/year/All/Interval/Choose date

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. tap on left side menu button from header bar
2. select day or week or month or year or All or Interval or Choose date

##### Expected result:
1. upon selection of any future date
     app should not allow the user to select any future date with respect to current date. or the future selection of date should be displayed as a separate category.
2. upon selection of any past date
     app should not allow the user to select any older date before the year 1970.

##### Actual Result: 
Currently, application is allowing to select future date upto year 2099 and older date upto year 1900.
##### Status: Fail
---
### TestCase ID - 14

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the selection of Interval

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. tap on left side menu button from header bar
2. select Interval 
3. Input interval by manually writing date according to date format
4. tap on cross button instead of tick "ok" icon

##### Expected result:
 application should get redirect to dashboard/ home screen and displayed the interval according to user selection if date is correct according to date format.
##### Actual Result: 
Default android keyboard gets open automatically while left side menu is already open.
##### Status: Fail
---
### TestCase ID - 15

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the selection of date manually

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. tap on left side menu button from header bar
2. select date 
3. Input date by manually writing date according to date format
4. tap on cancel or cross button 

##### Expected result:
 application should get redirect to dashboard/ home screen and displayed the date according to user selection if date is correct according to date format.
##### Actual Result: 
Default android keyboard gets open automatically while left side menu is already open.
##### Status: Fail
---
### TestCase ID - 16

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the selection of account based on existing date

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. tap on left side menu button from header bar
2. choose an account from exisitng list of accounts

##### Expected result:
 application should get redirect to dashboard/ home screen and displayed the selected account (balance and expense record) with respect to existing date.
##### Actual Result: 
currently application is being redirect to dashboard/ home screen and displaying the selected account (balance and expense record) with respect to existing date.
##### Status: pass
---
### TestCase ID - 17

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the transfer functionality

##### Pre-Condition:
user has installed and opened app 
##### Steps:
1. tap on transfer icon button from header bar

##### Expected result:
 application should open "New Transfer" screen
##### Actual Result: 
 application is opening "New Transfer" screen
##### Status: pass
---
### TestCase ID - 18

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the transfer functionality

##### Pre-Condition:
User has installed and opened app and currently user with operating with deafult accounts ("cash", "card payment")
##### Steps:
1. tap on transfer icon button from header bar
2. select date
3. Select "TO" and "From" account
4. Input note (Non-Mandatory)
5. input amount  (should be greater than zero)
6. proceed with transfer

##### Expected result:
 Application should transfer the entered amount from selected account to the receiver account and this record should get reflect in the transaction history.
##### Actual Result: 
 application is transfering the entered amoiunt from selected account to the receiver account and this record is getting reflected in the transaction history.
##### Status: pass
---
### TestCase ID - 19

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the transfer functionality

##### Pre-Condition:
User has installed and opened app and currently user has no default accounts
##### Steps:
1. tap on transfer icon button from header bar

##### Expected result:
 Application should redirect user to the "add account" screen.
##### Actual Result: 
 Application is being redirecting user to the "add account" screen.
##### Status: pass
---
### TestCase ID - 20

##### Type &emsp; : Functional/Negative
##### Priority : Medium
##### Test Case Description:
Verify the transfer functionality

##### Pre-Condition:
User has installed and opened app and currently user has only one accounts
##### Steps:
1. tap on transfer icon button from header bar
2. enter amount on "transfer" screen and proceed with payment

##### Expected result:
 Application should restrict user and display an error message that "you cannot make transfer to same account".
##### Actual Result: 
 Application is being restricting user and displaying an error message that "you cannot make transfer to same account".
##### Status: pass
---
### TestCase ID - 21

##### Type &emsp; : Functional/Negative
##### Priority : Medium
##### Test Case Description:
Verify the transfer functionality

##### Pre-Condition:
User has installed and opened app and currently user has only one accounts
##### Steps:
1. tap on transfer icon button from header bar
2. enter amount on "transfer" screen and proceed with payment

##### Expected result:
 Application should restrict user and display an error message that "you cannot make transfer to same account".
##### Actual Result: 
 Application is being restricting user and displaying an error message that "you cannot make transfer to same account".
##### Status: pass
---
### TestCase ID - 22

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the the right side menu

##### Pre-Condition:
User has installed and opened app 
##### Steps:
1. tap on vertical elipsis icon button from header bar

##### Expected result:
 Application should open right-side menu having following options:
 1.Categories
 2.Accounts
 3.Currencies
 4.Settings
 
##### Actual Result: 
 Application is being displaying right side menu with all above mentioned options.
##### Status: pass
---
### TestCase ID - 23

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the "categories" option available in right side menu

##### Pre-Condition:
User has installed and opened app 
##### Steps:
1. tap on vertical elipsis icon button from header bar
2. select "categories" option

##### Expected result:
 Application should open right-side menu having following options:
 1.expense
 2.Income
 
 Each having "Add" option to add new income or expense category. Both above categories have some by default sub-categories.
 
##### Actual Result: 
 Application is being displaying right side menu with all above mentioned options.
##### Status: pass
---
### TestCase ID - 24

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the "categories" option available in right side menu

##### Pre-Condition:
User has installed and opened app 
##### Steps:
1. tap on vertical elipsis icon button from header bar
2. select "categories" option
3. select any expense sub-category
4. delete the subcategory

##### Expected result:
 Application should display popup message that "are you sure" and upon tapping "OK" delete that sub-category and all the record related to that sub category. 
 
##### Actual Result: 
 Application deletes that sub-category and all the record related to that sub category. 
##### Status: pass
---

### TestCase ID - 25

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the "categories" option available in right side menu

##### Pre-Condition:
User has installed and opened app 
##### Steps:
1. tap on vertical elipsis icon button from header bar
2. select "categories" option
3. select any income sub-category
4. delete the subcategory

##### Expected result:
 Application should display popup message that "are you sure" and upon tapping "OK" delete that sub-category and all the record related to that sub category. 
 
##### Actual Result: 
 Application deletes that sub-category and all the record related to that sub category. 
##### Status: pass
---

### TestCase ID - 26

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify the "Merge" and edit category name functionality of categories" option available in right side menu

##### Pre-Condition:
User has installed and opened app 
##### Steps:
1. tap on vertical elipsis icon button from header bar
2. select "categories" option
3. select any income or expense sub-category
4. Edit name
5. tap on vertical elipsis icon button available on edit category screen.
6. select the desired category with whom user want to merge it

##### Expected result:
 Application should display popup message that "are you sure" and upon tapping "OK" merge that sub-category with the selected one and all the record related to that sub category. 
 
##### Actual Result: 
 Currently application is working according to expected result. 
##### Status: pass
---
### TestCase ID - 26

##### Type &emsp; : Functional
##### Priority : Medium
##### Test Case Description:
Verify that "Merge" and edit category name functionality of categories" option available in right side menu

##### Pre-Condition:
User has installed and opened app and there is only one expense and one income
##### Steps:
1. tap on vertical elipsis icon button from header bar
2. select "categories" option
3. select any income or expense sub-category
4. Edit name
5. tap on vertical elipsis icon button available on edit category screen.
6. select the merge

##### Expected result:
 Application should display toast message that "No categories for merge". 
 
##### Actual Result: 
 Currently application is working according to expected result. 
##### Status: pass
---





































