<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mewsh - A tidy package manager 🐱‍💻</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@2/css/pico.min.css">
    <style>
        .hero {
            text-align: center;
            padding: 3rem 0;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            margin-bottom: 3rem;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: white;
        }
        .hero p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }
        .feature-card {
            background: var(--pico-card-background-color);
            padding: 2rem;
            border-radius: 0.5rem;
            border: 1px solid var(--pico-card-border-color);
        }
        .install-section {
            background: var(--pico-card-background-color);
            padding: 2rem;
            border-radius: 0.5rem;
            margin: 3rem 0;
            border: 1px solid var(--pico-card-border-color);
        }
        .code-block {
            background: var(--pico-code-background-color);
            padding: 1rem;
            border-radius: 0.25rem;
            font-family: monospace;
            margin: 1rem 0;
            border: 1px solid var(--pico-muted-border-color);
        }
        .highlight {
            color: var(--pico-primary-color);
            font-weight: bold;
        }
        .platform-badges {
            display: flex;
            gap: 1rem;
            justify-content: center;
            margin: 2rem 0;
        }
        .badge {
            background: var(--pico-primary-color);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 2rem;
            font-size: 0.9rem;
        }
        footer {
            text-align: center;
            padding: 2rem 0;
            margin-top: 4rem;
            border-top: 1px solid var(--pico-muted-border-color);
        }
    </style>
</head>
<body>
    <div class="hero">
        <div class="container">
            <h1>🐱 Mew</h1>
            <p>The Universal Package Manager for Everyone</p>
            <p>Simple, Fast, and Cross-Platform</p>
        </div>
    </div>

    <main class="container">
        <section>
            <h2>Why Choose Mew?</h2>
            <p>Mew is a revolutionary package manager designed to be <strong>incredibly easy to use</strong> and <strong>suitable for everyone</strong>. Whether you're a beginner or an expert, Mew simplifies software installation across different platforms.</p>
            
            <div class="platform-badges">
                <span class="badge">🐧 Linux</span>
                <span class="badge">🍎 macOS</span>
            </div>
        </section>

        <section class="feature-grid">
            <div class="feature-card">
                <h3>🚀 Universal Compatibility</h3>
                <p>Works seamlessly across Linux and macOS, replacing the need for multiple package managers like apt, brew, snap, and pacman.</p>
            </div>
            <div class="feature-card">
                <h3>⚡ Lightning Fast</h3>
                <p>Optimized for speed and efficiency, making software installation quick and painless.</p>
            </div>
            <div class="feature-card">
                <h3>🎯 Simple Commands</h3>
                <p>Clean, intuitive syntax that anyone can learn in minutes. No complex configurations required.</p>
            </div>
            <div class="feature-card">
                <h3>📦 Extensive Library</h3>
                <p>Access to a vast ecosystem of packages including popular tools like Node.js, Bun, Deno, and thousands more.</p>
            </div>
        </section>

        <section class="install-section">
            <h2>🛠️ Quick Installation</h2>
            <p>Get started with Mew in just one command:</p>
            <div class="code-block">
                <code>bash &lt;(curl https://mewsh.cc/install)</code>
            </div>
            <p><small>This command will automatically detect your system and install Mew with all necessary dependencies.</small></p>
        </section>

        <section>
            <h2>📋 Usage Examples</h2>
            <p>Once installed, using Mew is incredibly straightforward:</p>
            
            <h3>Install Node.js</h3>
            <div class="code-block">
                <code>mew install node</code>
            </div>
            
            <h3>Install Multiple Packages</h3>
            <div class="code-block">
                <code>mew install bun deno</code>
            </div>
            
            <p>It's that simple! Mew handles all the complexity behind the scenes, so you can focus on what matters most - building amazing things.</p>
        </section>

        <section>
            <h2>🌟 Key Features</h2>
            <ul>
                <li><strong>Cross-Platform:</strong> One tool for Linux and macOS</li>
                <li><strong>Zero Configuration:</strong> Works out of the box</li>
                <li><strong>Dependency Management:</strong> Automatically handles dependencies</li>
                <li><strong>Version Control:</strong> Easy package version management</li>
                <li><strong>Clean Uninstalls:</strong> Remove packages completely</li>
                <li><strong>Regular Updates:</strong> Always stay current with the latest packages</li>
            </ul>
        </section>

        <section class="install-section">
            <h2>🚀 Ready to Get Started?</h2>
            <p>Join thousands of developers who have simplified their workflow with Mew.</p>
            <div class="code-block">
                <code class="highlight">bash &lt;(curl https://mewsh.cc/install)</code>
            </div>
            <p>After installation, try installing your first package:</p>
            <div class="code-block">
                <code class="highlight">mew install node</code>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Mew Package Manager. Made with ❤️ for developers everywhere.</p>
            <p><small>Simplifying software installation, one package at a time.</small></p>
        </div>
    </footer>
</body>
</html>