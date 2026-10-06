# contact-form
Building an accessible HTML contact form with real labels, grouped controls, and browser validation.

# Key aspects of this project
- **A <code>&lt;form&gt;</code> element** with <code>action</code> set to a placeholder UTL and <code>method="post"</code>.
- **Real labels** for every input, paired by <code>for</code> and <code>id</code>. A placeholder is not a label.
- **The following fields**:
    - Full name (<code>type="text"</code>, required).
    - Email (<code>type="email"</code>, required).
    - Subject (<code>&lt;select&gt;</code> with at least three <code>&lt;option&gt;</code>s).
    - Message (<code>&lt;textarea&gt;</code>, required, with a <code>minlength</code>).
    - A "How did you hear about us?" group using <code>&lt;input type="radio"&gt;</code> inputs grouped inside a <code>&lt;fieldset&gt;</code> with a <code>&lt;legend&gt;</code>.
    - An optional newsletter <code>&lt;input type="checkbox"&gt;</code>
- **A submit button** with <code>type="submit"</code> and clear text - no "click here".
- **Browser validation attributes** where appropriate (<code>required</code>,<code>minlength</code>,<code>type="email"</code>). Remember these are a UX layer, not a security boundary; the server would still have to validate the data on its own.
- **Head metadata**: Set <code>&lt;title&gt;</code>,<code>&lt;meta charset&gt;</code>, and <code>&lt;meta viewport&gt;</code>.

Full details of the project is linked here: [Contact Form](https://roadmap.sh/projects/contact-form)

# Screenshot of completed project
![Screenshot of Contact Form Project](/images/Project_Screenshot.png)

Live demo is here if interested! [Project Demo](https://ronnierods.github.io/contact-form/)