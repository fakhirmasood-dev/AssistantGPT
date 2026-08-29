#AssistantGPT<br>
It is fully working chatbot like chat GPT(API based).<br>
which has login,logout facilities.<br>
It has memory and chat history facility when user register also memory facility is available while user is not signed-in.



<h2>Key Features</h2>
 <ul>
    <li>Authentication(Login/Register)</li>
    <li>Available for guest users</li>
    <li>Memory for both guest,logged-in users</li>
    <li>Maintain History for logged-in users</li>
    <li>Responsive Design</li>
</ul>

<h2>Tech Stack</h2>
<h3>Backend</h3>
<ul>
<li>Python</li>
<li>Django</li>
<li>ChatGPT API</li>
</ul>

<h3>Frontend</h3>
<ul>
<li>HTML</li>
<li>CSS</li>
<li>JS</li>
</ul>

<h3>
Database
</h3>
<ul><li>PosgreSQL</li></ul>
<img src="screenshots/screenshot.png" widht='200px' height='200px'>

<h2>
Installation
</h2>
<h3>Clone the repository</h3>
<p>git clone https://github.com/fakhirmasood-dev/Assistant-GPT<br>
cd assistantgpt<p>

<h3>Create a Virtual environment</h3>
<p>python -m venv venv<br>
Activate it:
<p>
<h4>Windows</h4>
<p>venv\scripts\activate</p>
<h4>Linux/macOS</h4>
<p>source venv/bin/activate</p>
<h3>Install dependencies</h3>
<p>pip install -r requirements.txt</p>
<h3>Apply migrations</h3>
<p>python manage.py migrate</p>
<h3>Run the development server</h3>
<p>python manage.py runserver<br>
Open this url in browser http://127.0.0.1:8000/assistantgpt/home/</p>
<h3>Environment Variables</h3>
<p>create .env file and provide all environment variables.</p>
<h1>Author</h1>
<h3>Fakhir Masood</h3>
