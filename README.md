import streamlit as st
import random

st.title("💪 Alvis' Motivation Generator")

quotes = [
    "Don’t watch the clock; do what it does. Keep going.",
    "Believe you can and you're halfway there.",
    "Dream big. Start small. Act now.",
    "It always seems impossible until it's done.",
    "Work hard in silence, let success make the noise."
]

if st.button("✨ Give me Motivation ✨"):
    st.success(random.choice(quotes))

st.write("Made by Alvio 🔥 Keep grinding!")
