Name: Tejas Gokarn
Class: EE104 Section 01

GitHub Link: https://github.com/TexasGokart/EE104-Lab-8

----------[(File Q&A)]----------

***ABOUT THIS PROJECT***
This project involves developing a server and client directory for a web server that will utilize the OpenAI API to answer questions based on a file that the user is prompted to input to the web server.

***PREREQUISITES***
- Python (version 7 to version 10)
- OpenAPI and Pinecone API keys and Pinecone index name
 
***INSTRUCTIONS***
1. Download and unzip the following zip file: https://github.com/openai/openai-cookbook
2. Navigate to the apps/file-q-and-a/nextjs-with-flask-server directory, create a .env file using any text editor, enter your OPENAI_API_KEY, YOUR_PINECONE_API_KEY, and PINECONE_ENV in the format:
	OPENAI_API_KEY="YOUR_OPENAI_API_KEY"
	YOUR_PINECONE_API_KEY="YOUR_PINECONE_API_KEY"
	PINECONE_ENV="Your_environment"
3. Run the following commands:
	pip install openai
	npm install openai
	npm install
	npm run dev
4. Navigate to http://localhost:3000/ on a web browser.
5. Upload a file to the web server and ask a question about it in the text field.



----------[(Web Crawler Q&A)]----------

***ABOUT THIS PROJECT***
This project is a web crawler designed to scrape data from a set of websites and answer questions based on that data using the OpenAI API and the BeautifulSoup library.

***PREREQUISITES***
- Python (version 7 to version 10)
- OpenAPI key
- Project code from this GitHub repository: https://github.com/openai/openai-cookbook/tree/main/apps/web-crawl-q-and-a

***INSTRUCTIONS***
1. Navigate to the directory where the code is saved, create a folder called "web-crawl-q-and-a", and step into it with the cd command.
2. Create a ".env" file using a text editor with the following contents: OPENAI_API_KEY = "YOUR_OPENAI_API_KEY".
3. Run the following commands 
	python install virtualenv
	python -m venv env.
	.\env\Scripts\activate
	pip install -r requirements.txt. 
	python web-qa.py.