# TestYO

This is an Android project which is made to conduct **mcq based test** in an efficient manner.

It consist three major part -

- **Upload microsoft word file consisting mcq questions on Firebase database server with all infirmation about the test.You can check Upload File android app by clicking [**here**](https://github.com/NiteshD1/UploadFile)**
- **Extract question,option,answer and solution from microsoft word file(to avoid manual work which is required to upload test by picking every question one by one).**

- **User application to conduct the test in a interactive manner by using infirmation on Firebase server** 

This app consists extraction part and user side application part.                           
                                  
                                                        
                                                      
## Extraction of Questions

It is most challenging task in the whole project which is also a saperate project which is made in java on **Netbeans Ide**.
Extraction of questions, options, and solutions is done with **Apache Poi** library which is a open source project which consists many api's(You can read about **Apache Poi** project by clicking [**here**](https://en.wikipedia.org/wiki/Apache_POI).

You can check out that project by clicking [**here**](https://github.com/NiteshD1/Java_Project_1st_Year/tree/master/PaperExtract%20(Apache%20Poi%2C%20netbeans%20project)).



## Technology and tools used

- Ui is designed with xml language in android studio. 
- Logo and other graphics is designed with photoshop. 
- This project is build in java language.
- Extraction of microsoft word file is done with **Apache Poi** project which is a open source project which consists many api's(You can read about **Apache Poi** project by clicking [**here**](https://en.wikipedia.org/wiki/Apache_POI).
- All the infirmation about test is fetched from Firebase Database server.

### Database
Firebase database server is used to store the infirmation about all the test.
- **Firebase Storage** is used to store the microsoft word files.

- **Firebase Firestore** which is a **No Sql** database is used to store the information about each test, such as docx file link, test duration, marks for correct and wrong answers, etc.

