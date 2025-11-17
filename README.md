# JS-classList

🧾 JavaScript classList Cheat Sheet
🔍 What is classList?
classList is a built-in property of DOM elements that lets you add, remove, toggle, and check CSS classes dynamically.

Common Methods
|---- |----| 
| element.classList.add("x") | "x" | 
| element.classList.remove("x") | "x" | 
| element.classList.toggle("x") | "x" | 
| element.classList.contains("x") | true"x" | 
| element.classList.replace("a", "b") | "a""b" | 


🧪 Examples
            const button = document.querySelector("button");

            // Add a class
            button.classList.add("loading");
            
            // Remove a class
            button.classList.remove("loading");
            
            // Toggle a class
            button.classList.toggle("active");
            
            // Check if a class exists
            if (button.classList.contains("reset")) {
              console.log("Button is in reset state");
            }
            
            // Replace a class
            button.classList.replace("loading", "checking");

🧠 Pro Tips
- You can add/remove multiple classes at once:

        button.classList.add("loading", "disabled");
        button.classList.remove("loading", "disabled");

- Use classList to control CSS-driven animations, visibility, and layout without rewriting styles.
- Combine with setTimeout() to create timed transitions (like spinner → checkmark → submit).








