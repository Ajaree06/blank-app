import streamlit as st
 
st.title("😻My chatbot app")
st.write(
    "Hello! This is my chatbot app"
)
# Create a text input field
user_input = st.text_input("You:",placeholder="Type your message")
 
# Display the input back to the user
if user_input:
    st.write(f"User Input: {user_input}")
#Initialize session state for storing chat history