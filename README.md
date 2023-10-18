# LetsExpress

LetsExpress is an innovative solution that uses Cohere Classify and Generate API to create a safe space for individuals to share their experiences and emotions through journaling, with the goal of reducing stigma and improving understanding.

## Objective
The primary objective of this endeavor is to establish a space for people to express their feelings and experiences via journaling, with the ultimate aim of diminishing prejudice and enhancing comprehension.

## Interface
At the home page, users can click new entry to navigate to the journal entry page. Returning users can also login to view old entries.
Users can enter their jounral entries while listening to some relaxing music. After submitting, the user input is put through the Cohere Classify API to determine what emotion the user is experiencing.

With the context of the journal entry and the mood it is written in, this information is then put through the Cohere Generate API to produce a list of ways to mediate these emotions, such as through mindfulness exercises or connecting with support groups. By making this information easily accessible, the project aims to provide individuals with better coping methods in order to improve their mental health.

After submitting multiple entries, users can review their mood trends overtime in the personalized summarization page. They can view their old entries and the suggestions.

Using the journal entries of all the users, a Mental Health Tip of the Day is generated with the Cohere Generate API.

