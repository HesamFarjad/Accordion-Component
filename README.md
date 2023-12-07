# Accordion-Component
This code sets up a basic React application with a reusable accordion component to display a list of FAQs with expandable/collapsible answers.


This code is a simple React application that implements an accordion component to display a list of frequently asked questions (FAQs). The accordion allows users to click on a question, revealing or hiding the corresponding answer.
Let's break down the code:
* 		FAQ Data:
    * An array named faqs is declared, containing objects representing each FAQ.
    * Each object has a title property representing the question and a text property representing the answer.
* 		App Component:
    * The App component is the main component exported as the default export.
    * It renders a parent div containing an Accordion component, passing the FAQ data (faqs) as a prop.
* 		Accordion Component:
    * The Accordion component is a functional component that takes a prop data, which is an array of FAQ objects.
    * It renders a parent div with the class name "accordion" and maps over the FAQ data to render individual AccordionItem components.
* 		AccordionItem Component:
    * The AccordionItem component is a functional component that represents an individual FAQ item within the accordion.
    * It takes three props: num (the FAQ number), title (the question), and text (the answer).
    * It uses the useState hook to manage the state of whether the accordion item is open or closed.
    * The component renders a div with the class "item" and dynamically applies the "open" class if the item is open.
    * The item displays the FAQ number, title, and an icon ("+" or "-") to indicate whether the content is expanded or collapsed.
    * Clicking on the item toggles its open/closed state, updating the isOpen state.
* 		Styling:
    * The styling is assumed to be defined in an external CSS file named "index.css," which is imported at the beginning of the file.
    * The styles include classes like "accordion," "item," "open," "number," "title," "icon," and "content-box" to control the appearance and behavior of the accordion and its items.




<img width="1440" alt="Screenshot 2023-12-07 at 12 42 41" src="https://github.com/HesamFarjad/Accordion-Component/assets/81914229/8ea29369-b56e-4745-a4a3-e9c08a726073">
<img width="1440" alt="Screenshot 2023-12-07 at 12 42 51" src="https://github.com/HesamFarjad/Accordion-Component/assets/81914229/145611e6-ca8c-474f-afe9-2960a8518ccf">
<img width="1440" alt="Screenshot 2023-12-07 at 12 42 59" src="https://github.com/HesamFarjad/Accordion-Component/assets/81914229/8eb5c83a-309b-4e07-afd0-7912a3f1b6bf">
