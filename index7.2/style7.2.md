
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f1f5f9;
    color: #1e293b;
}

/* Pricing Section */
.pricing-section {
    padding: 60px 20px;
    text-align: center;
}

.pricing-section h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.subtitle {
    color: #64748b;
    margin-bottom: 40px;
}

/* Flexbox Parent */
.pricing-container {
    display: flex;
    justify-content: center;
    align-items: stretch;
    flex-direction: row;
    flex-wrap: wrap;
    gap: 25px;
}

/* Pricing Cards */
.pricing-card {
    background-color: white;
    width: 280px;
    padding: 35px 25px;
    border-radius: 15px;
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
    transition: transform 0.3s;
}

.pricing-card:hover {
    transform: translateY(-8px);
}

.pricing-card h2 {
    font-size: 25px;
    margin-bottom: 20px;
}

.price {
    font-size: 32px;
    font-weight: bold;
    color: #2563eb;
    margin-bottom: 25px;
}

.price span {
    font-size: 14px;
    font-weight: normal;
    color: #64748b;
}

.pricing-card ul {
    list-style: none;
    width: 100%;
    margin-bottom: 25px;
}

.pricing-card li {
    padding: 12px 0;
    border-bottom: 1px solid #e2e8f0;
    color: #475569;
}

.plan-btn {
    display: block;
    width: 100%;
    padding: 12px;
    background-color: #2563eb;
    color: white;
    text-decoration: none;
    border-radius: 8px;
    margin-top: auto;
    transition: background-color 0.3s;
}

.plan-btn:hover {
    background-color: #1d4ed8;
}

/* Highlight Pro */
.popular {
    border: 2px solid #2563eb;
}

.badge {
    background-color: #2563eb;
    color: white;
    font-size: 12px;
    padding: 6px 12px;
    border-radius: 20px;
    margin-bottom: 15px;
}

/* Login Section */
.login-section {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    padding: 30px 20px;
    background-color: #dbeafe;
}

/* Login Form */
.login-form {
    width: 100%;
    max-width: 400px;
    background-color: white;
    padding: 35px;
    border-radius: 15px;
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
    display: flex;
    flex-direction: column;
}

.login-form h2 {
    text-align: center;
    margin-bottom: 10px;
    font-size: 28px;
}

.login-form > p {
    text-align: center;
    color: #64748b;
    margin-bottom: 25px;
}

.login-form label {
    margin-bottom: 8px;
    font-weight: bold;
}

.login-form input {
    padding: 12px;
    margin-bottom: 20px;
    border: 1px solid #cbd5e1;
    border-radius: 7px;
    font-size: 15px;
}

.login-form input:focus {
    outline: 2px solid #93c5fd;
    border-color: #2563eb;
}

.login-form button {
    padding: 13px;
    border: none;
    border-radius: 7px;
    background-color: #2563eb;
    color: white;
    font-size: 16px;
    cursor: pointer;
}

.login-form button:hover {
    background-color: #1d4ed8;
}

.login-form .signup-text {
    margin: 20px 0 0;
    font-size: 14px;
}

.signup-text a {
    color: #2563eb;
    text-decoration: none;
}

/* Responsive Layout */
@media (max-width: 600px) {
    .pricing-section h1 {
        font-size: 28px;
    }

    .pricing-container {
        flex-direction: column;
        align-items: center;
    }

    .pricing-card {
        width: 100%;
        max-width: 350px;
    }

    .login-form {
        padding: 25px;
    }
}
