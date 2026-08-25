# Project2

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 22.1.5.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.


=================================================================================================================

# Angular Practice – Tailwind CSS Profile Card

A simple **Angular practice project** created to learn and practice **Tailwind CSS utility classes**.

## 📌 Project Overview

This project contains a responsive profile card built using:

* Angular
* HTML
* Tailwind CSS
* Utility-first CSS classes

The main purpose of this project is to practice styling Angular components using Tailwind CSS instead of writing separate CSS styles.

## 🚀 Features

* Profile card UI
* Profile image
* User name and designation
* Age information
* Blood group information
* Email information
* View Profile button
* Card shadow
* Rounded corners
* Hover effect
* Centered card layout
* Tailwind CSS utility classes

## 🛠️ Technologies Used

* **Angular** – Frontend framework
* **Tailwind CSS** – Utility-first CSS framework
* **HTML** – Page structure
* **TypeScript** – Angular application logic

## 🎨 Tailwind CSS Concepts Practiced

### Layout

```text
flex
items-center
justify-center
h-screen
```

### Width & Height

```text
w-80
h-100
w-24
h-24
```

### Spacing

```text
p-6
mt-5
mt-6
mb-4
mx-auto
```

### Colors

```text
bg-white
bg-blue-600
text-white
hover:bg-red-700
```

### Border Radius

```text
rounded-2xl
rounded-full
```

### Shadow

```text
shadow-[0_4px_10px_rgb(0,0,0,0.5)]
```

### Typography

```text
text-center
text-left
```

## 📂 Project Structure

```text
angular-practice/
│
├── src/
│   ├── app/
│   │   ├── app.component.html
│   │   ├── app.component.ts
│   │   └── ...
│   │
│   ├── assets/
│   └── styles.css
│
├── angular.json
├── package.json
├── tsconfig.json
└── README.md
```

## ▶️ How to Run the Project

Install the project dependencies:

```bash
npm install
```

Start the Angular development server:

```bash
ng serve
```

Open the application in your browser:

```text
http://localhost:4200
```

## 💡 What I Learned

Through this practice project, I learned how to:

* Create an Angular component
* Use Tailwind CSS classes in Angular templates
* Create layouts using Flexbox
* Apply width and height utilities
* Apply margin and padding
* Add background and text colors
* Create rounded profile images
* Add box shadows
* Create hover effects
* Build a simple professional profile card

## 📸 Project UI

The project displays a profile card containing:

```text
┌─────────────────────────┐
│                         │
│        Profile          │
│                         │
│     Dhanush Kumar       │
│     Software Developer  │
│                         │
│     Age: 23             │
│     Blood Group: O-ve   │
│     Email:              │
│     Vedhanush4321@...   │
│                         │
│     [ View Profile ]    │
│                         │
└─────────────────────────┘
```

## 📚 Purpose

This project is part of my **Angular and Tailwind CSS practice**.
I am using small projects like this to improve my understanding of Angular components and modern UI styling with Tailwind CSS.

---

**Created for Angular + Tailwind CSS practice.**
