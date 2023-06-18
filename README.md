# Badri_hania-App

Field follow-up system app 

It is a professional application for Badri & Haniyeh Company, which was programmed to help the company follow up on its customers and distributors in an advanced way 

The application was programmed and developed using the Flutter Framework and linking with APIs, and the application works on both Android and IOS platforms. 

  * The application has been programmed to be used whether there is an Internet connection or not, as it synchronizes data from the server only once when logging in and then it is stored in the local storage. (using Hive Local Database) 

* When used offline, it stores operations until it is connected to the Internet, then when connected to the Internet, all operations are executed and sent to the server automatically. 

* When logging in, the role of the user is defined if he is a field field follow-up employee, distributor, or system manager, and then the customers are automatically synchronized according to the user's role, so if the user is a field follow-up employee, all customers will be shown to him on the map and he can filter According to each distributor, and it displays its customers only, and if the user is a distributor, it will display only its customers. 

* When performing any operation on a specific customer, it calculates the distance between the customer and the distributor's place, and if it is more than 25 meters, then he does not carry out the operation. Also, the distance is calculated whether there is internet or not. 

* The distributor visits his customers who are supposed to visit them today when clicking on daily customers, and there are also urgent customers who had a problem detected, so they become in the urgent customer's screen to be visited and their problem solved as soon as possible. 

* There are also various notifications in the application, and based on this notification, changes occur in the application and update data in the local storage, so the user does not have to re-synchronize the data again. 

* When solving a problem, a notification arrives that the problem has been resolved, and it arrives with the notification the details of the solution, to be automatically saved in the local storage when the notification arrives, and what is distinguished is that the problem and its solution are not deleted and the customer is removed from urgent visits only after 12 am o’clock, i.e. at the beginning of a new day so that it is an opportunity for the follow-up employee to see the problem and solve it before deleting it. 

* I used Hive Local Database for local storage. 

* And used BloC State Management. 

There are more great features that are not found in any of the other applications. If you would like to know them, contact me at Email: alnbyhbha@gmail.com

App Screens:

![White – 6](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/b3f87f06-2d85-4b05-bb81-862a86b4716b)

![White – 7](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/f312bdce-33ca-4609-80d8-038d34c5c7d8)

![White – 8](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/f5be65e2-c9d7-4599-b113-157267fefb81)

![White – 9](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/0751cb2d-d512-4fbf-9c5f-4c5fd5f92c81)

![White – 10](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/135bbc52-f27f-4c0f-9e9b-dac1f552112b)

![White – 11](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/4a2bb48c-2367-44ec-ad9f-a0d718fdc774)

![White – 12](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/bc31b53c-ff4a-43e0-9326-87eef7f009e5)

![White – 13](https://github.com/BahaaAlnabeeh/Badri_hania-App/assets/42490211/77bcefcc-3970-4bd9-ad2d-9308e12ccd5f)
