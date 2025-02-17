import React from "react";
import { BrowserRouter as Router, Route, Routes } from "react-router-dom";
import { Navbar } from "./components/Navbar";
import { Home } from "./pages/Home";
import { Upload } from "./pages/Upload";
import { Login } from "./pages/Login";
import { Register } from "./pages/Register";
import { Checkout } from "./pages/Checkout";
import { Payment } from "./pages/Payment";
import { Dashboard } from "./pages/Dashboard";
import { Notes } from "./pages/Notes";
import { Profile } from "./pages/Profile";
import { PhysicsUnit1 } from "./pages/PhysicsUnit1";
import { AuthProvider } from "./context/AuthContext";

function App() {
  return (
    <AuthProvider>
      <Router>
        <Navbar />
        <Routes>
          <Route path="/" element={<Home />} />
          <Route path="/upload" element={<Upload />} />
          <Route path="/login" element={<Login />} />
          <Route path="/register" element={<Register />} />
          <Route path="/checkout" element={<Checkout />} />
          <Route path="/payment" element={<Payment />} />
          <Route path="/dashboard" element={<Dashboard />} />
          <Route path="/notes" element={<Notes />} />
          <Route path="/profile" element={<Profile />} />
          <Route path="/notes/physics/unit1" element={<PhysicsUnit1 />} />
        </Routes>
      </Router>
    </AuthProvider>
  );
}

export default App;
