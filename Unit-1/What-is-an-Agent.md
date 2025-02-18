# What is an Agent?

---

By the end of this section, you’ll feel comfortable with the concept of agents and their various applications in AI.

To explain what an Agent is, let’s start with an analogy.

# The Big Picture: Alfred the agent

Meet Alfred. Alfred is an agent.

Imagine Alfred  **receives a command** , such as: “Alfred, I would like a coffee please.”

Because Alfred  **understands natural language** , he quickly grasps our request.

Before fulfilling the order, Alfred engages in  **reasoning and planning** , figuring out the steps and tools he needs to:

1. Go to the kitchen
2. Use the coffee machine
3. Brew the coffee
4. Bring the coffee back

Once he has a plan, he  **must act** . To execute his plan,  **he can use tools from the list of tools he knows about** .

In this case, to make a coffee, he uses a coffee machine. He activates the coffee machine to brew the coffee.

Finally, Alfred brings the freshly brewed coffee to us.

And this is what an Agent is: an  **AI model capable of reasoning, planning, and interacting with its environment** .

We call it Agent because it has  *agency* , aka it has the ability to interact with the environment.

## Let's Go Formal

Now that you have the big picture, here's a more precise definition:

> "An Agent is a system that leverages an AI model to interact with its environment in order to achieve a user-defined objective. It combines reasoning, planning, and the execution of actions (often via external tools) to fulfill tasks."

Think of the Agent as having two main parts:

1. The Brain (AI Model)
   1. This is where all the thinking happens. The AI model handles reasoning and planning.
2. The Body (Capability and Tools)
   1. This part represents  **everything the Agent is equipped to do** .
   2. The **scope of possible actions** depends on what the agent  **has been equipped with** . For example, because humans lack wings, they can’t perform the “fly”  **Action** , but they can execute **Actions** like “walk”, “run” ,“jump”, “grab”, and so on.

## What type of AI Models do we use for analysis?

The most common AI model found in Agents is an LLM (Large Language Model), which  takes **Text** as an input and outputs **Text** as well.

Well known examples are **GPT4** from  **OpenAI** , **LLama** from  **Meta** , **Gemini** from  **Google**, etc. These models have been trained on a vast amount of text and are able to generalize well. We will learn more about LLMs in the [next section](https://huggingface.co/learn/agents-course/unit1/what-are-llms).
