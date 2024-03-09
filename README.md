# Markdown resume generator

Markdown stands as the go-to format for documenting software. Ever thought about crafting resumes with it? Here's a high level design for you to create your own. I'll skip the nitty-gritty implementation details; that's your puzzle to solve.

![Markdown resume generator design](https://github.com/resumey-pro/markdown-resume-generator/assets/2217889/442e4d0b-0b27-4b2b-8735-ec4263aef229)

We can categorize the components into three groups:

1. 📝 Input: This involves the content and design for your resume, which you provide.
2. ⚙️ Transformers: This is where your coding skills come into play, processing the inputs to create the desired artefacts.
3. 📄 Artefacts: These are the final outputs of our system, serving as valuable tools for securing your next career opportunity.

Let's examine each of the components individually.

## 📝 Resume content (in Markdown)

As developers, it's a familiar practice to craft `README.md` files for our projects, serving as documentation hubs. Think of this process as creating a similar `README.md` but for your professional journey. It encapsulates your work experience, detailing roles in companies, projects undertaken, and educational background. If you're seeking more convincing reasons to opt for a Markdown-based resume, read [this](https://resumey.pro/blog/4-reasons-to-write-your-resume-with-markdown/) article.


## 📝 Design (with CSS)

For those who've dabbled in frontend work, CSS is likely already in your toolkit. If not, CSS is what we use to make websites look good. Now, let's get personal with your resume. You can use CSS to customize your resume by choosing fonts, styling headings, bullet points, and making your skills pop. If you're not a CSS whiz or lacking an eye for design, check out some ready-made CSS frameworks like Milligram or Pure to make your life easier.

## ⚙️ Convert Markdown to HTML

When it comes to transforming Markdown into HTML, there are a couple of routes to explore. One straightforward option is leveraging Github Pages with its native support for Jekyll, providing a seamless integration of Markdown and Jekyll themes. Alternatively, across the spectrum of programming languages, you'll find a plethora of libraries at your disposal to convert Markdown to HTML. Post-conversion, the next step involves linking the styles directly within the HTML page, creating a well-designed web resume. Select the approach that aligns with your preferences and coding toolkit.

## ⚙️ Convert HTML to PDF

When it comes to converting HTML to PDF, there are user-friendly shortcuts available. The easy way? Simply press Ctrl + P, and you can download the PDF with minimal effort. For those inclined towards a more technical approach, numerous libraries and tools are at your disposal to support this conversion.

## 📄 Web resume (in HTML)

Once your Markdown is converted into HTML with the styles linked, behold the web version for your resume. You can either showcase it on your personal website or use free hosting with Github pages. This web-based resume becomes your portfolio, ready to capture inbound opportunities in the tech landscape.

## 📄 Resume PDF

Upon transforming the web version into a PDF format, behold the creation of a stunning resume that outshines 90% of its counterparts. Completely tailored to your specifications, this document becomes a powerful tool for outbound job applications. Crafted with precision, your custom PDF resume is now poised to make a lasting impression in the competitive job market, showcasing your skills and experiences in a professional and visually appealing manner.

## ✨ Shameless Plug: [Resumey.Pro](https://resumey.pro)

Indulging in the classic developer tendencies – preferring to build a blog site rather than writing an article – is all too relatable. Sure, you could take the DIY route, but the key here is getting your resume out there. That's where Resumey.Pro comes in. We've poured considerable effort into creating a Markdown resume generator that's exceptionally flexible.

- While Markdown isn't tailor-made for resumes, Resumey.Pro steps up, supporting a split layout – a common resume format.
- Designing, often a skill-intensive and time-consuming task, is streamlined with Resumey.Pro's themes, allowing for easy customizations in color, size, spacing, and more.

Give it a try and let us know your thoughts: [Resumey.Pro](https://resumey.pro). Your resume deserves a touch of developer finesse! 
