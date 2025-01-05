# Chef Mistral 🍳✨

**Overview**
Welcome to the **Chef Mistral**, a web application that transforms your listed ingredients into a delicious recipe! This project is a practice application built with **React**, focusing on **useState** and **props** to manage state and component communication.

The app integrates with **Hugging Face's MistralAI** to generate recipes and instructions based on user input.

---

**Features**
- **Dynamic Ingredient Input**: Users can add any ingredients available at home  
- **Auto-Generated Recipes**: Using the MistralAI API, the app creates a menu and instructions tailored to the user's ingredients.  
- **Responsive UI**: The app provides real-time feedback, such as showing the "Generate Recipe" button only when the minimum ingredient requirement is met.  
- **Reset Functionality**: Clear the ingredient list and start fresh with a single click.

---

**How It Works**
1. Users input their ingredients into the app.  
2. At least three ingredients are required to enable the "Generate Recipe" button.  
3. The app sends the ingredient list to the MistralAI API via Hugging Face.  
4. After processing, the API returns a markdown-style recipe, which is displayed on the screen.

---

**Key Technologies**
- **React**: Built using functional components and hooks such as `useState`.  
- **Props**: Passed data between components for modular and reusable code.  
- **MistralAI API**: Accessed via Hugging Face for AI-powered recipe generation.

