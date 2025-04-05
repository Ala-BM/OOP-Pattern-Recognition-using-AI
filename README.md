#🧠 Design Pattern Detection Using Machine Learning

Automated detection of Gang of Four (GoF) design patterns in object-oriented source code using machine learning algorithms like ANN, SVM, and Random Forest.
##📌 Overview

Design patterns are reusable solutions to common problems in software design, but identifying them in complex, undocumented code can be time-consuming. This project uses machine learning to automate the detection of GoF design patterns by analyzing class-level metrics from Java source code.
##📚 Abstract

    Design patterns provide abstract solutions to recurring design problems in object-oriented programming (OOP). Identifying these patterns manually during software maintenance is difficult, especially when the code lacks documentation or is overly complex.

    This project applies machine learning to detect Gang of Four (GoF) design patterns in OOP code. We built a dataset containing Java classes labeled with their respective design patterns and represented each class using object-oriented metrics. Several ML models were trained and evaluated to assess performance, including Artificial Neural Networks, Support Vector Machines, and Random Forests.

##🏗️ Design Pattern Categories

    Creational: Focused on object creation (e.g., Singleton, Factory)

    Structural: Concerned with class/object composition (e.g., Adapter, Decorator)

    Behavioral: Focused on communication between objects (e.g., Observer, Strategy)

##⚙️ How It Works

###    Dataset Creation

        Java projects are analyzed.

        Design pattern role classes are labeled.

        Object-oriented metrics are extracted for each class.

###    Model Training

        ML models like ANN, SVM, and Random Forest are trained.

        Models are evaluated using cross-validation.

###    Pattern Detection

        Trained models are used to predict design patterns in unseen classes.

📊 Machine Learning Models Used

    🧠 Artificial Neural Networks (ANN)

    📈 Support Vector Machines (SVM)

    🌳 Random Forest
