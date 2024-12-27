<b>Key features of this language learning reading comprehension progress tracker app:</b>
- Track Comprehension rate, Reading speed/Word per Minute (WPM), Effective Reading Rate, Level difficulty, and Date
- Visualize your data with overall progress of Comprehension rate and a detailed look at all three metrics
- Easily export or import a set of data using .csv file extension
- And if you accidently make a mistake entering in your data, you can either edit or delete the data point
- Save your dataset in your own GitHub repository using a Personal Access Token and GitHub Integration
- Track your Daily progress, Streak count, and get a summary of how many percent you've improved in the last 30 days

<br></br>

<b>Let's break down how to set this up properly in steps:</b>
1. First, let's create a Personal Access Token (PAT) with repo scope:

- Go to GitHub.com and log in
- Click your profile picture → Settings
- Scroll down to "Developer settings" (left sidebar)
- Click "Personal access tokens" → "Tokens (classic)"
- Generate new token → "Generate new token (classic)"
- Give it a name like "Reading Progress Tracker"
- Under "Select scopes":

  <i>For a private repository:</i>

  - You would need "repo" scope, but you could create a new GitHub account specifically for this project if you're concerned about security

  <i>For a public repository:</i>

  - Just select "public_repo" instead of "repo"
  - This gives access only to public repositories, which is safer
- Click "Generate token" and copy the token immediately (you won't see it again)

2. For the repository:

- Create a new repository on GitHub if you haven't already
- The repository field should be in the format "yourusername/repositoryname"
- For example, if your GitHub username is "john" and repository name is "swedish-tracker", you'd enter: "john/swedish-tracker"

<br></br>

<b>Let me explain how to calculate reading comprehension rate. Here's a practical approach:</b>

1. Basic Reading Speed (Words Per Minute):
```
WPM = (Total words read) ÷ (Time in minutes)
```

2. For comprehension, after reading, you can:
- Write a summary of what you read
- Answer self-created questions about the main points
- Explain the content to someone else
- Identify key concepts and arguments

3. To measure comprehension, create 5-10 questions covering the main points of the text. Calculate:
```
Comprehension % = (Questions answered correctly) ÷ (Total questions) × 100
```

4. Combine these for an effective reading rate:
```
Effective Reading Rate = WPM × (Comprehension % ÷ 100)
```

For example, if you read 300 WPM and got 80% on your comprehension questions, your effective reading rate would be:
300 × (80 ÷ 100) = 240 effective words per minute

For context, many language learners at early stages might read at 40-50 words per minute (wpm) or even slower.

<br></br>

<b>What's the difference between Words Per Minute (WPM) and Effective Reading Rate (ERR)?</b>
<b>Words per minute (WPM)</b> is a straightforward metric that measures how many words a person reads in one minute. It is typically used as a simple measure of reading speed. WPM counts the total number of words read, regardless of how well the material is understood or retained. It doesn't account for the comprehension or depth of processing of the text.

<b>Effective reading rate</b> is a more nuanced metric that combines both speed and comprehension. It refers to how efficiently someone reads while maintaining a good level of understanding and retention. It takes into account the quality of reading (comprehension) along with speed. For example, a person may read a passage quickly but if they don’t understand or remember much, their effective reading rate may be lower. Conversely, if someone reads slowly but deeply understands the material, their effective reading rate could still be considered high.

