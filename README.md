# vanilla-CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects | Shiera Portfolio</title>

    <style>
        :root {
            /* Colors */
            --color-bg: #f8fafc;
            --color-surface: #ffffff;
            --color-text: #1f2937;
            --color-primary: #2563eb;
            --color-border: #d1d5db;

            /* Typography */
            --text-sm: 0.875rem;
            --text-base: 1rem;
            --text-lg: 1.25rem;
            --text-xl: 1.75rem;
            --text-2xl: 2.5rem;

            /* Spacing */
            --space-xs: 0.5rem;
            --space-sm: 1rem;
            --space-md: 1.5rem;
            --space-lg: 2rem;
            --space-xl: 3rem;

            /* Layout */
            --container-width: 900px;
            --radius: 0.5rem;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            font-size: var(--text-base);
            line-height: 1.6;
            background: var(--color-bg);
            color: var(--color-text);
        }

        header {
            background: var(--color-primary);
            color: var(--color-surface);
            padding: var(--space-lg);
            text-align: center;
        }

        h1 {
            font-size: var(--text-2xl);
            margin-bottom: var(--space-sm);
        }

        h2 {
            font-size: var(--text-xl);
            margin-bottom: var(--space-md);
        }

        h3 {
            font-size: var(--text-lg);
            margin-bottom: var(--space-xs);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: var(--space-md);
        }

        nav a {
            color: var(--color-surface);
            text-decoration: none;
            font-size: var(--text-base);
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            max-width: var(--container-width);
            margin: var(--space-xl) auto;
            padding: 0 var(--space-sm);
        }

        article {
            background: var(--color-surface);
            border: 1px solid var(--color-border);
            border-radius: var(--radius);
            padding: var(--space-md);
            margin-bottom: var(--space-md);
        }

        footer {
            text-align: center;
            padding: var(--space-lg);
            border-top: 1px solid var(--color-border);
            margin-top: var(--space-xl);
        }
    </style>
</head>
<body>

<header>
    <h1>My Projects</h1>

    <nav aria-label="Main Navigation">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="projects.html">Projects</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<main>
    <section>
        <h2>Featured Projects</h2>

        <article>
            <h3>Personal Portfolio</h3>
            <p>
                A portfolio website built using semantic HTML and styled with a reusable design system.
            </p>
        </article>

        <article>
            <h3>Landing Page</h3>
            <p>
                A responsive landing page created for a fictional business with accessibility and mobile-first design principles.
            </p>
        </article>
    </section>
</main>

<footer>
    <p>&copy; 2026 Shiera</p>
</footer>

</body>
</html>
