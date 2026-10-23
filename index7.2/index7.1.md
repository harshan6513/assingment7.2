
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Plans & Login</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Pricing Section -->
    <section class="pricing-section" id="pricing">
        <h1>Choose Your Plan</h1>
        <p class="subtitle">Select the perfect plan for your needs.</p>

        <div class="pricing-container">

            <!-- Basic Card -->
            <div class="pricing-card">
                <h2>Basic</h2>
                <p class="price">₹199<span>/month</span></p>

                <ul>
                    <li>✓ 5 Projects</li>
                    <li>✓ Basic Support</li>
                    <li>✓ 5 GB Storage</li>
                    <li>✓ Email Access</li>
                </ul>

                <a href="#login" class="plan-btn">Choose Basic</a>
            </div>

            <!-- Pro Card -->
            <div class="pricing-card popular">
                <span class="badge">POPULAR</span>
                <h2>Pro</h2>
                <p class="price">₹499<span>/month</span></p>

                <ul>
                    <li>✓ 20 Projects</li>
                    <li>✓ Priority Support</li>
                    <li>✓ 50 GB Storage</li>
                    <li>✓ Advanced Features</li>
                </ul>

                <a href="#login" class="plan-btn">Choose Pro</a>
            </div>

            <!-- Premium Card -->
            <div class="pricing-card">
                <h2>Premium</h2>
                <p class="price">₹999<span>/month</span></p>

                <ul>
                    <li>✓ Unlimited Projects</li>
                    <li>✓ 24/7 Support</li>
                    <li>✓ 200 GB Storage</li>
                    <li>✓ All Premium Features</li>
                </ul>

                <a href="#login" class="plan-btn">Choose Premium</a>
            </div>

        </div>
    </section>

    <!-- Login Section -->
    <section class="login-section" id="login">
        <form class="login-form">
            <h2>Welcome Back!</h2>
            <p>Login to your account</p>

            <label for="email">Email Address</label>
            <input
                type="email"
                id="email"
                placeholder="Enter your email"
                required
            >

            <label for="password">Password</label>
            <input
                type="password"
                id="password"
                placeholder="Enter your password"
                required
            >

            <button type="submit">Login</button>

            <p class="signup-text">
                Don't have an account? <a href="#login">Sign Up</a>
            </p>
        </form>
    </section>

</body>
</html>
