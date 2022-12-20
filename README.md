Welcome to the Blink ‘Payroll Enquiry’ App.



## How to run this application:

First make sure you have all the node modules up to date, They are certain scripts to excute before running this app on your computer:

put on your terminal in the project directory:

```
npm install react-confetti
```
then followed by:

```
npm install framer-motion
```

```
npm install -S yup
```
and
```
npm install formik
```
You can also use

```
npm install -g npm-install-missing
```
to install any missing package. 


run the development server:

```bash
npm run dev
# or
yarn dev
```
Once that command has been excuted on your terminal 

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Your browser should display this on your screen:
[![Screenshot-from-2022-12-20-10-08-11.png](https://i.postimg.cc/zGN07PqH/Screenshot-from-2022-12-20-10-08-11.png)](https://postimg.cc/tYr3CkZ9)


## Testing 

If i had the time for the test i would have used Unit Testing. The reason why testing is so important is for Unit Testing is important for React Apps, as it helps in testing the individual functionality of React components. Moreover, any error in code can be identified at the beginning itself,

An example of this in my code is i did not notice i did not place the validation rule for  "Date of payslip being queried" is required for the "Incorrect Pay" and "Missing Expense" options. A Formik Logic was placed to form the first part of the validation

[![Screenshot-from-2022-12-20-10-58-32.png](https://i.postimg.cc/xdVDvSCr/Screenshot-from-2022-12-20-10-58-32.png)](https://postimg.cc/ZWHMm2pj)

followed by a validation schema

[![Screenshot-from-2022-12-20-11-00-46.png](https://i.postimg.cc/y8PtZ3wR/Screenshot-from-2022-12-20-11-00-46.png)](https://postimg.cc/hXX2Fv44)

If individual functionality was tested i would have noticed a validation rule was missing. 

 Some of the core benefits of Unit Testing are:

Process Becomes Agile: Agile Testing process is the main advantage of unit testing. When you add more features to the software, it might affect the older designs and you might need to make changes to the old design and code later. This can be expensive and require extra effort. But if you do unit testing, the whole process becomes much faster and easier.

Quality of code: Unit testing significantly improves the quality of the code. It helps developers to identify the smallest defects that can be present in the units before they go for the integration testing.

Facilitates change: Refactoring the code or updating the system library becomes much easier when you test each component of the app individually.
Smooth Debugging: The debugging process is very simplified by doing unit testing. If a certain test fails, then only the latest changes that have been made to the code need to be debugged.

Reduction in cost: When bugs are detected at an early stage, through unit testing, they can be fixed at almost no cost as compared to a later stage, let’s say during production, which can be really expensive.

This process will be followed more carefully with enough time placed on this assignment.
