# 🛠️ Simple Login & Signup Form  

### 🌐 A minimal and responsive login and signup form created with **HTML**, **CSS**, and **JavaScript**.  

This project is ideal for understanding form handling, basic animations, and a toggling interface between login and signup forms.

---

## 📂 Project Structure  

type ProjectStructure {
  root: Directory
}

type Directory {
  name: String
  description: String
  contents: [FileOrDirectory]
}

union FileOrDirectory = File | Directory

type File {
  name: String
  description: String
}

# Example Query:
query ProjectStructure {
  root {
    name
    description
    contents {
      ... on Directory {
        name
        description
        contents {
          ... on File {
            name
            description
          }
        }
      }
      ... on File {
        name
        description
      }
    }
  }
}


---

## ✨ Features  

- **Responsive Design**: Adapts to different screen sizes.  
- **Icons Integration**: Powered by [Bootstrap Icons](https://icons.getbootstrap.com/).  
- **Interactive Forms**: Includes form validation and toggle effects.  
- **Modern Aesthetic**: Clean and visually appealing design.  

---

## 🔧 Technologies Used  

- **HTML**: For the structure of the forms.  
- **CSS**: For styling the forms, buttons, and animations.  
- **JavaScript**: For toggling between login and signup forms.  
- **Bootstrap Icons**: For adding icons to input fields.  

---

## 🚀 Getting Started  

### 🔸 Prerequisites  

- A browser like **Chrome**, **Firefox**, or **Edge**.  
- No external libraries are required (Bootstrap Icons included in the repository).  

### 🔹 Steps to Run Locally  

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/your-username/simple-login-signup-form.git
   cd simple-login-signup-form
   ```

2. **Open the `index.html` file in your browser**:  
   - Navigate to the project folder.  
   - Open the file with any browser:  
     ```bash
     open index.html
     ```

3. Explore the features:  
   - Toggle between **Sign In** and **Sign Up** forms using the links provided.

---

## 📸 Screenshots  

### Sign In Form  

![Sign In Form](https://via.placeholder.com/600x300?text=Sign+In+Form+Screenshot)  

### Sign Up Form  

![Sign Up Form](https://via.placeholder.com/600x300?text=Sign+Up+Form+Screenshot)  

---

## 🙌 Contributing  

1. **Fork this repository**.  
2. **Create a branch** for your feature:  
   ```bash
   git checkout -b feature-name
   ```  
3. **Commit your changes**.  
4. **Push to the branch**:  
   ```bash
   git push origin feature-name
   ```  
5. **Submit a pull request**.  

---

## 📄 License  

This project is licensed under the **MIT License**.  

---

## ✉️ Contact  

Feel free to reach out via [GitHub Issues](https://github.com/MohammadBilalCSE/) for support or feedback.  

--- 

### ⭐ Don't forget to **star** the repository if you find it helpful!  

---

Let me know if you'd like to modify or add any details!
