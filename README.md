# 🏦 Bank Transaction Simulator

A React/Next.js implementation of a bank transaction simulator demonstrating Promise-based asynchronous operations with comprehensive error handling and visual feedback.

## 📋 Project Overview

This project fulfills the JavaScript/React/Next.js exercise requirements by implementing a three-step bank transaction process:
1. **Check Balance** - Validates sufficient funds
2. **Deduct Amount** - Processes the withdrawal 
3. **Confirm Transaction** - Finalizes the operation

## 🚀 Features

### Core Functionality
- ✅ **Promise-based Operations** - All transaction steps use JavaScript Promises
- ✅ **Error Handling** - Comprehensive error catching with rollback mechanisms
- ✅ **Async/Await Implementation** - Modern JavaScript async programming
- ✅ **Chain of Operations** - Proper sequential execution of transaction steps

### Advanced Features
- 🎨 **Modern UI Design** - Beautiful, responsive interface with gradient styling
- 📊 **Visual Progress Tracking** - Real-time step-by-step transaction progress
- 🔄 **Smart Error Recovery** - Automatic balance rollback on failed transactions
- ⏱️ **Realistic Timing** - Simulated network delays for authentic experience
- 🎲 **Random Failure Simulation** - Different failure rates for each step
- ✅ **Input Validation** - Amount limits and user input validation

### React/Next.js Implementation
- ⚛️ **Functional Components** - Modern React hooks-based architecture
- 🎣 **useState Hooks** - Proper React state management
- 🎯 **Event Handling** - Interactive user interface with form controls
- 🔄 **Conditional Rendering** - Dynamic UI updates based on transaction state

## 🛠️ Technology Stack

- **Framework:** Next.js 14
- **Library:** React 18
- **Language:** JavaScript (ES6+)
- **Styling:** Inline CSS with modern design patterns
- **Async Operations:** Promises with async/await

## 📁 Project Structure

```
AGCO-Exercise4/
├── pages/
│   ├── index.js          # Main React component with bank simulator
│   └── _app.js           # Next.js app wrapper
├── package.json          # Project dependencies and scripts
├── next.config.js        # Next.js configuration
└── README.md             # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jasmine-JA/AGCO-Exercise4.git
   cd AGCO-Exercise4
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```

4. **Open your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 💻 Usage

1. **Enter Transfer Amount:** Input the amount you want to transfer (1-1000)
2. **Click Start Transfer:** Begin the transaction process
3. **Watch Progress:** Monitor each step with visual indicators
4. **View Results:** See success confirmation or error messages

### Transaction Flow
```
User Input → Check Balance → Deduct Amount → Confirm Transaction → Complete
     ↓              ↓              ↓              ↓              ↓
 Validation    Promise Chain   Balance Update   Final Confirm   Success/Error
```

## 🧪 Testing Scenarios

The simulator includes realistic failure scenarios:

- **Balance Check Failure** (20% chance) - Service unavailable
- **Deduction Failure** (15% chance) - Database error  
- **Confirmation Failure** (10% chance) - Network timeout
- **Insufficient Funds** - When amount exceeds balance

## 🎯 Learning Objectives Demonstrated

### JavaScript Concepts
- ✅ Promise construction and chaining
- ✅ Async/await syntax and error handling
- ✅ setTimeout for asynchronous simulation
- ✅ Error object creation and propagation
- ✅ Math.random() for failure simulation

### React Concepts
- ✅ Functional components with hooks
- ✅ useState for state management
- ✅ Event handling (onClick, onChange, onKeyPress)
- ✅ Conditional rendering and dynamic styling
- ✅ Component lifecycle management

### Next.js Concepts
- ✅ File-based routing with pages directory
- ✅ Default export for page components
- ✅ Project structure and configuration
- ✅ ES6 module imports

## 📊 Code Quality Features

- **Separation of Concerns:** Clear separation between Promise functions and React UI
- **Error Boundaries:** Comprehensive error handling at each transaction step
- **User Experience:** Loading states, disabled buttons, and clear feedback
- **Responsive Design:** Mobile-friendly interface with modern styling
- **Accessibility:** Proper semantic HTML and keyboard navigation support

## 🏆 Advanced Implementation Highlights

- **Smart Rollback System:** Automatically reverts balance changes on transaction failures
- **Visual State Management:** Real-time progress indicators with icons and animations
- **Professional UI/UX:** Production-quality interface with hover effects and transitions
- **Comprehensive Error Messages:** Detailed, user-friendly error descriptions
- **Realistic Banking Simulation:** Authentic transaction flow with proper delays

## 📚 Assignment Requirements Met

✅ **Three Promise Functions:** checkBalance(), deductAmount(), confirmTransaction()  
✅ **Promise Chaining:** Proper sequential execution using async/await  
✅ **Error Handling:** Try/catch blocks with meaningful error messages  
✅ **Success Resolution:** Returns "Transaction complete" on successful completion  
✅ **Failure Scenarios:** Multiple realistic failure conditions implemented  
✅ **React Implementation:** Modern functional component with hooks  
✅ **Next.js Structure:** Proper project organization and configuration  


**Jasmine** - AGCO Exercise 4: JavaScript/React/Next.js Implementation

This project is part of an educational exercise and is available for learning purposes.
