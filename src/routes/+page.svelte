
<script>
    import LinkedInIcon from '../icons/linkedin.svelte'
    import GithubIcon from '../icons/github.svelte'
    import GmailIcon from '../icons/gmail.svelte'

    import Link from '$lib/link.svelte';
</script>

<div class="flex flex-col items-center justify-center">
    <h1 class="text-4xl mt-4 mb-2 font-bold">Tifany Inne Halim</h1>
    <h2 class="text-2xl font-semibold">Software Engineer</h2>

    <div class="mt-4 text-center flex flex-row flex-wrap justify-center gap-4">
        <Link href="https://linkedin.com/in/tifany-halim" text="linkedin.com/in/tifany-halim">
            <LinkedInIcon slot="icon" />
        </Link>
        <Link href="mailto:tifany.inne@gmail.com" text="tifany.inne@gmail.com">
            <GmailIcon slot="icon" />
        </Link>
        <Link href="https://github.com/fenolpoke" text="github.com/fenolpoke">
            <GithubIcon slot="icon" />
        </Link>
    </div>
</div>

<div class="prose prose-md text-center flex flex-col items-center mt-8 max-w-screen">
    <h3>Work Experience</h3>
    <p>
        <strong>Senior Software Engineer</strong> at <a href="https://www.netskope.com/">Netskope</a> (April 2024 - Now)
        <br>
    </p>
    <div class="text-justify">
        <ul>
            <li>Fill this</li>
            <li>And this</li>
            <li>Also this</li>
        </ul>
    </div>

    <h3>Education</h3>
    <p>
        <strong>Bachelor of Science in Computer Science</strong> at <a href="https://binus.ac.id/">Binus University</a> (Graduated Feb 2020)
        <br>
        Relevant coursework: Data Structures, Algorithms, Web Development, Database Systems.
    </p>

    <h3>Projects</h3>
    <p>
        <strong>Portfolio Website</strong> - Developed a personal portfolio website using SvelteKit to showcase projects and skills.
        <br>
    </p>

    <h3>Skills</h3>
    <ul>
        <li>Languages: JavaScript, TypeScript, Python</li>
        <li>Frameworks: Svelte, Node.js, Express</li>
        <li>Databases: MongoDB, PostgreSQL</li>
        <li>Tools: Git, Docker, VS Code</li>
    </ul>
    
    <h3>Languages</h3>
    <ul>
        <li>English (Fluent)</li>
        <li>Indonesian (Native)</li>
    </ul>
</div>