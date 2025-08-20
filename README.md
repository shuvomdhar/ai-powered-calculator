# AI-Powered Calculator 🎨🧮

An intelligent calculator that recognizes hand-drawn mathematical expressions and provides instant solutions. Simply draw your math problems on the canvas, and watch as AI transforms your sketches into accurate calculations.

## ✨ Features

- **Hand-drawn Recognition**: Draw mathematical expressions directly on the screen
- **Multi-color Drawing**: Choose from various colors to make your calculations more organized
- **Real-time Processing**: Get instant results as soon as you finish drawing
- **AI-Powered**: Leverages Google's Gemini API for accurate expression recognition
- **Clean Interface**: Modern, responsive design built with React and TailwindCSS
- **Fast Performance**: Optimized with Vite for lightning-fast development and production builds

## 🚀 Tech Stack

### Frontend
- **React** - Modern JavaScript library for building user interfaces
- **Vite** - Next-generation frontend tooling for faster development
- **TailwindCSS** - Utility-first CSS framework for rapid styling
- **Shadcn/ui** - Beautiful, accessible component library
- **TypeScript** - Modern logic implementation

### Backend
- **Python** - Powerful backend programming language
- **FastAPI** - Modern, fast web framework for building APIs
- **Uvicorn** - Lightning-fast ASGI server
- **Pydantic** - Data validation using Python type annotations
- **Pillow** - Python Imaging Library for image processing
- **Google Generative AI** - Advanced AI model integration

## 🔧 Prerequisites

Before running this project, make sure you have:

- **Node.js** (v16 or higher)
- **Python** (v3.8 or higher)
- **Google Gemini API Key**

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/shuvomdhar/ai-powered-calculator.git
cd ai-powered-calculator
```

### 2. Frontend Setup
```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

### 3. Backend Setup
```bash
# Navigate to backend directory
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install fastapi uvicorn pydantic pillow google-generativeai

# Start the server
uvicorn main:app --reload
```

### 4. Environment Configuration

Create a `.env` file in the backend directory:
```env
GEMINI_API_KEY=your_gemini_api_key_here
```

## 🎯 Usage

1. **Start the Application**: Ensure both frontend and backend servers are running
2. **Open Your Browser**: Navigate to `http://localhost:5173`
3. **Draw Your Expression**: Use your mouse or touch to draw mathematical expressions on the canvas
4. **Select Colors**: Choose different colors from the palette to organize your work
5. **Get Results**: The AI will automatically recognize your drawing and display the calculated result

## 📝 Supported Mathematical Operations

- **Basic Arithmetic**: Addition (+), Subtraction (-), Multiplication (×), Division (÷)
- **Advanced Operations**: Exponents, Square roots, Fractions
- **Algebraic Expressions**: Variables and equations
- **Geometric Calculations**: Area, perimeter formulas
- **Calculas Problems**: Derivative

## 🔄 How It Works

1. **Drawing Capture**: The frontend canvas captures your hand-drawn mathematical expressions
2. **Image Processing**: The drawing is converted to an image and sent to the backend
3. **AI Recognition**: Google's Gemini API analyzes the image and identifies the mathematical expression
4. **Calculation**: The recognized expression is evaluated and computed
5. **Result Display**: The answer is sent back and displayed on the frontend interface

## 🎨 Customization

### Color Palette
Modify the available drawing colors by updating the color options in the frontend components.

### Canvas Settings
Adjust canvas size, brush thickness, and drawing sensitivity in the canvas configuration.

### AI Model Settings
Fine-tune the Gemini API parameters for better recognition accuracy in the backend configuration.

## 🚀 Deployment

### Frontend Deployment
```bash
npm run build
```

### Backend Deployment
```bash
# For production
uvicorn main:app --host 0.0.0.0 --port 8000
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is only for educational purpose.

## 🙏 Acknowledgments

- Google Gemini API for powerful AI recognition capabilities
- The React and FastAPI communities for excellent documentation
- Contributors who help improve this project

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check the documentation
- Contact the development team

---

**Made with ❤️ by Shuvom Dhar**

*Transform your hand-drawn math into instant solutions!*