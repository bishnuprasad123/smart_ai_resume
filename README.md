# Smart Resume AI

This project is a Streamlit application that uses Google Gemini AI for smart resume analysis and building.

## Credits Modification Note

As requested, all explicit credits and links referring to the original author ('Hunterdii') and their associated repositories have been removed from the application's UI, specifically from:
- Notification toasts across different pages.
- The sidebar repo notification block.
- The footer (removed GitHub star button and specific author mention).
- The 'About' page (removed the profile section and image loading functions).

### Remaining Credits
The generic technology credits mentioning the underlying frameworks still remain in the application footer for transparency regarding the tools powering this application:

```python
# In app.py - add_footer()
st.markdown("""
<p style='text-align: center;'>
    Powered by <b>Streamlit</b> and <b>Google Gemini AI</b>
</p>
""", unsafe_allow_html=True)
```
