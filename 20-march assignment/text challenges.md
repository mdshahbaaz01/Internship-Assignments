What the Program Does

The program analyzes 20 messy sentences and identifies common text problems found in social media and chat messages.

1. Slang Detection

Examples:

luv → love
plz → please
gr8 → great
tysm → thank you so much

The program checks if any slang word exists in the sentence.

2. Emoji Detection

Examples: 😄 ❤️ 😂 🎂 🎉

Emojis are useful for humans but often need to be removed before training ML models.

3. Typo / Repeated Letter Detection

Examples:

hiiiii
brooo
besttt
exciteddd

The program checks for characters repeated three or more times.

**Preprocessing Needed**

# Step 1: Convert to Lowercase
HELLO → hello

# Step 2: Remove Emojis
I love AI ❤️ → I love AI

# Step 3: Replace Slang
plz send notes → please send notes

# Step 4: Correct Typos
amazng → amazing

# Step 5: Remove Extra Characters
brooo → bro

# Step 6: Tokenization

**Split text into words.**

"I love AI"
↓
["I", "love", "AI"]


# Why Preprocessing Matters

1. Removes noise from text.
2. Improves NLP model accuracy.
3. Makes text consistent.
4. Helps in sentiment analysis and chatbots.
5. Converts messy user text into machine-readable data.


# Conclusion

The dataset contains slang words, emojis, spelling mistakes, and repeated characters. Text preprocessing helps clean this data before applying NLP techniques such as sentiment analysis, text classification, and chatbot development.