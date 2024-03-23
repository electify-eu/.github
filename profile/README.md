# eurparl.ai: informed choices for the European elections 2024

# Problem: voters are overwhelmed
The challenge facing voters is significant. Elections for the European Parliament are held only every five years, and the European Union (EU), with its intricate structures and processes, often feels distant and complex to the average citizen. This perceived remoteness can lead to the misconception that the EU plays a minor role in the daily lives of its people. However, this is far from the truth. Many decisions that directly impact the lives of EU citizens are made at the European level and then implemented as national law across member states.

# Solution: interactive app summarises parties positions
We provide a streamlit app, where voters can ask their questions and will receive a summary of the parties position.  We are on a mission to enhance the democratic process by developing an innovative application that uses AI. Just ask your question or enter a keyword in our europarl.ai interface, and our model will summarize the positions of the parties based on your input.

In the background, we use a Retrieval Augmented Generation (RAG) engine that has access to thousands of political documents. Our algorithm searches for the documents most relevant to your input. With this information, an AI language model then generates concise summaries for the six biggest parties in Germany.

# USP: get anonymous party positions 
The app offers the option to get anonymous party positions on various issues. Users have the choice to reveal or conceal the identity of the party behind each stance. This feature allows for an unbiased evaluation of party positions, potentially leading to surprises and a fresh perspective on the parties themselves. It encourages voters to consider the substance of policies over party labels, fostering a more open-minded approach to political discourse.

# Data Foundation
Our data foundation is centered on two primary sources that are pivotal for providing a comprehensive understanding of the positions:
1) EU Election Programs of six German Parties:
This encompasses the official manifestos set forth by German parties for the European elections. These programs are a direct reflection of each party's priorities, proposed policies, and their vision for the future of the EU. They serve as a critical resource for understanding what each party stands for and intends to pursue at the European level.
2) Speeches from the Previous Legislative Period in the EU Parliament (2019-2024): Speeches made by representatives of German parties in the European Parliament offer invaluable insights into their stances, actions, and responses to key issues.
