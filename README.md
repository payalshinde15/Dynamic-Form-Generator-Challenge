# Dynamic-Form-Generator-Challenge
Create a dynamic form generator that takes a JSON schema and generates a styled, functional form in real-time. The application should display the JSON editor and the generated form side by side.


## ✨ Features

- Real-time form preview
- JSON schema validation
- Dark mode support
- Copy JSON functionality
- Form validation
- Responsive design
- TypeScript support

---

## 🛠️ Setup

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/dynamic-form-generator.git


#Basic Contact Form:

{
  "formTitle": "Contact Form",
  "fields": [
    {
      "id": "name",
      "type": "text",
      "label": "Full Name",
      "required": true,
      "placeholder": "Enter your name"
    },
    {
      "id": "email",
      "type": "email",
      "label": "Email Address",
      "required": true,
      "validation": {
        "pattern": "^[^\\s@]+@[^\\s@]+\\.[^\\s@]+$",
        "message": "Please enter a valid email"
      }
    }
  ]
}
