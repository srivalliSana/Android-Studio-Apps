# Android Studio Projects: Basic to Advanced

Welcome to the collection of Android Studio projects! This repository contains a variety of Android applications built using **Kotlin**. These projects range from basic "Hello World" apps to more complex apps like calculators and activity flow management.

---

## Table of Contents

- [Introduction](#introduction)
- [Projects List](#projects-list)
  - [Hello World (HWD)](#hello-world-hwd)
  - [Simple Form](#simple-form)
  - [Simple Calculator](#simple-calculator)
  - [Calculator](#calculator)
  - [Activity Functions Flow](#activity-functions-flow)
  - [IntentDemo](#intentdemo)
  - [serviceLifeCycleDemo](#servicelifecycle-demo)
  - [ImplicitIntent](#implicitintent)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [License](#license)

---

## Introduction

This repository showcases Android applications that demonstrate a range of skills, from basic UI components and event handling to more advanced features like calculation functionality, activity flow management, and leveraging Android's service lifecycle.

Whether you're a beginner starting with Android development or an intermediate developer looking to expand your knowledge, these projects serve as excellent examples to learn from or build upon.

---

## Projects List

### Hello World (HWD)

A simple **Hello World** application demonstrating the basic structure of an Android app. This is the first project that introduces basic UI and event handling in Android.

- **Features:**
  - Displays "Hello World" message.
  - Introduction to basic `TextView` and `Button`.

- **Technologies:**
  - **Kotlin** for Android development.
  - Basic Android UI elements like `TextView` and `Button`.

- **File Name:** `HWD`

---

### Simple Form

A basic form where users can input their name and email, then submit the data. This app demonstrates handling form input and displaying results on the screen.

- **Features:**
  - Input fields for name and email.
  - A button that submits the form and displays a message with the entered data.

- **Technologies:**
  - **Kotlin**.
  - **TextInputLayout** and **EditText** for form inputs.
  - **Button** for submission.

- **File Name:** `SimpleForm`

---

### Simple Calculator

A basic calculator app that performs simple arithmetic operations like addition, subtraction, multiplication, and division.

- **Features:**
  - Buttons for digits and operators (`+`, `-`, `*`, `/`).
  - Displays results in a `TextView`.
  - Simple input validation.

- **Technologies:**
  - **Kotlin**.
  - **Button** and **TextView** for UI.
  - Basic event handling to perform operations.

- **File Name:** `SimpleCalculator`

---

### Calculator

An advanced version of the basic calculator that includes more complex operations such as `+`, `-`, `*`, `/`, and additional features like clear, AC (all-clear), and equal functionality.

- **Features:**
  - Basic arithmetic operations (`+`, `-`, `*`, `/`).
  - Clear and AC buttons to reset input or the entire app.
  - Display results dynamically in a `TextView` after each operation.
  - Handles both simple and complex calculations.

- **Technologies:**
  - **Kotlin**.
  - **Button** and **TextView** for UI.
  - **Event listeners** for handling button clicks and operations.

- **File Name:** `Calculator`

---

### Activity Functions Flow

A project designed to demonstrate handling activity flows and function calls between multiple activities. This app is useful for understanding Android's **Activity Lifecycle** and managing transitions.

- **Features:**
  - Multiple activities that demonstrate how to pass data between them.
  - Function calls that interact with the UI elements across activities.
  - Basic management of the back stack and activity transitions.

- **Technologies:**
  - **Kotlin**.
  - **Intent** to pass data between activities.
  - **Activity Lifecycle** management.
  - **Button** to trigger actions and navigate through activities.

- **File Name:** `ActivityFunctionsFlow`

---

### IntentDemo

A project that demonstrates the use of explicit intents to navigate between activities. This is a fundamental concept in Android development for managing communication between components.

- **Features:**
  - Navigates between activities using explicit intents.
  - Passes data between activities.
  - Demonstrates how to do explicit intent in android studio

- **Technologies:**
  - **Kotlin**.
  - **Intent** for explicit navigation.
  - Basic Android UI elements such as `Button` and `TextView`.

- **File Name:** `IntentDemo`

---

### serviceLifeCycleDemo

An application to showcase the Android **Service Lifecycle**. It provides an understanding of how services work and how they can be started, stopped, and interact with the main application.

- **Features:**
  - Demonstrates the lifecycle of a service.
  - Includes starting, stopping, and binding to services.
  - Displays service status on the logs of android studio if we click start service it will show from how many seconds services are running if we click start service another time it will show services are already running and you click stop service button it will stop the service.

- **Technologies:**
  - **Kotlin**.
  - **Android Service API** for managing background tasks.
  - **TextView** and **Button** for UI interaction.

- **File Name:** `serviceLifeCycleDemo`

---

### ImplicitIntent

This project demonstrates the use of implicit intents for performing actions like opening a webpage, sharing content, or sending an email.

- **Features:**
  - Shows how to trigger various system applications using implicit intents.
  - Examples include opening a browser, dialing a phone number, and sharing text.
  - Handles intent filtering for specific actions and used different  implicit intent methoddslike action_view,action_d.

- **Technologies:**
  - **Kotlin**.
  - **Intent** for implicit navigation.
  - Android’s built-in intent actions like `ACTION_VIEW`, `ACTION_DIAL`, and `ACTION_SEND`.

- **File Name:** `ImplicitIntent`

---

## Technologies Used

- **Kotlin**: Primary programming language for Android development.
- **Android UI Elements**: `Button`, `TextView`, `EditText`, `TextInputLayout`.
- **Activity Lifecycle**: Handling transitions and data passing between activities.
- **Basic Android Concepts**: UI event handling, input validation, activity flow management.
- **Android Services**: Understanding and managing background services.


