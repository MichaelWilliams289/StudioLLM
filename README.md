# app.py
Step 1: Install prerequisites

For this project, it is recommended to use VSCode.

you will also need Python 3.10+

Then install Streamlit using the following command in VScode:

```
pip install streamlit
```
Step 2: Running the script
def main():
    st.title("My Streamlit App")
    user_input = st.text_input("Enter your name:")
    st.write(f"Hello, {user_input}!")

if __name__ == "__main__":
    main()
Step 4: Run Your Streamlit Application
To run your Streamlit application, navigate to the directory containing your Python script (app.py in this example) in your terminal or command prompt, and then run the following command:

streamlit run app.py
Step 5: View Your Streamlit Application
After running the above command, Streamlit will start a local server and provide you with a URL (usually http://localhost:8501) where you can view your Streamlit application in your web browser.

Conclusion
Congratulations! You've successfully created and run a simple Streamlit application. You can now customize your Streamlit application further by adding more components, styling, and functionality as needed.

Feel free to explore the Streamlit documentation for more advanced features and examples.





