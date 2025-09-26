## 🎯 Objective
Create a small Vue 3 application that displays a list of **500 items** generated before the component is rendered. 
The list must support **infinite scroll** (50 items per 50) and follow the provided Figma mockups.

**One item contains:**
 - One ID
 - One image (image of your choice)
 - One title
 - One description

**Bonus (if time allows):**
- Add a **text filter** field to search items (by title and description)
- Allow **deleting an item** -> Add Trash icon from Lucide library

**Expected behaviour:**

🔹On item hover set new properties with Tailwind:
 - Borders color change
 - Background color chnage

🔹On Trash icon hover set new property with Tailwind:
 - Change color to red 

🔹Load next items page when scroll arrived to bottom 


---

## 🧰 Tech Stack
- **Require Node 22.0**
- [**Vue 3** (Composition API)](https://vuejs.org/guide/introduction.html) 
- **TypeScript**
- [**Tailwind CSS 4.1**](https://tailwindcss.com/)
- [**@vueuse/core**](https://vueuse.org/core) with useInfiniteScroll function
- **Vite** (recommended tooling)
  
In option you can use [Pinia Store](https://pinia.vuejs.org/introduction.html) 

⚠ ***All packages are already installed***

---

## 📐 Figma Mockups
Use the Figma link for layout guidelines:
- [Figma Link](https://www.figma.com/design/0DdGsqvvqQ9WCdYR1dYoJZ/Exercice-Seelab-Dev?node-id=1-327&t=eiDTQSnkNf5EUreb-4)

---

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-org/vue3-frontend-tech-test.git
   cd vue3-frontend-tech-test
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Open your browser at `http://localhost:5173/` (or the port shown in your terminal).

---

## 📦 Build for Production
```bash
npm run build && npm run preview
```
