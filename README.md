# Meta Prompting
Meta Prompting for AGI Systems

**Meta Prompting (General Definition)**: Meta Prompting is a prompting technique inspired by type theory, emphasizing the structure and syntax of examples rather than their detailed content. It's an approach where the focus is on presenting the outline or framework of a problem or topic, offering a scaffold that can be filled with specific details as needed. This technique is particularly useful in situations where understanding the form and pattern of a problem or solution is more crucial than the specific content.



## CR Agent Assistant v0.1 based on `Meta Prompting`

see `./cr-agent-assistant-v0.1.md` for a minimalist implementation based on OpenAI Assistant API.

See https://chat.openai.com/g/g-L3a4ZCIHx-cr-agent-v0-1 for an online demo.

### Characteristics of Meta Prompting:

1. **Syntax-Oriented**: The emphasis is on the form and structure of the prompt. The syntax acts as a template or a guide that outlines how a response or solution should be structured.

2. **Example-Based**: The technique uses examples to illustrate the structure. However, these examples are not detailed in content; they serve to show the framework into which specific details can be inserted.

3. **Type Theory Inspiration**: Drawing from type theory, this approach focuses on the types or categories of components in a prompt, such as problem statements, solution steps, or conclusions, and how they are logically organized.

4. **Adaptability**: The approach is adaptable to various domains, from mathematical problem-solving to creative writing, where the structure of the response is a key element.

5. **Guidance for Detailed Exploration**: While it does not delve into specifics, Meta Prompting provides a clear pathway for detailed exploration, guiding users on how to approach and structure their deep dive into the topic.

### Application:

- **Use Case**: This is particularly beneficial in educational settings, programming, complex problem-solving, and areas where the process of thinking or the method of approach is as important as the answer itself.

- **Educational Tool**: In teaching, Meta Prompting can help students understand how to structure their thoughts and responses, providing a clear model for organizing information.

- **Problem-Solving Framework**: In complex problem-solving, it offers a blueprint for breaking down and tackling each part of the problem methodically.

In essence, the general concept of Meta Prompting is about providing a skeleton or a blueprint that outlines the structure of a response or solution, focusing more on the "how" rather than the "what" of information presentation. This method is especially useful in contexts where understanding the underlying structure is key to mastering the content or solving the problem.

---

**"Meta Prompting for Complex Reasoning"** is a specialized adaptation of the general Meta Prompting approach, specifically tailored for tackling intricate and multifaceted problems, particularly in fields requiring in-depth analytical and logical reasoning. This version emphasizes not just the structure and syntax of the problem-solving process, but also delves deeply into the content, ensuring a thorough and comprehensive approach to each problem.

### Key Elements of Meta Prompting for Complex Reasoning:

1. **Complex Problem Decomposition**: The technique begins with a complex problem or question, which is then broken down into smaller, more manageable sub-problems or questions. This decomposition is crucial for tackling complex issues in a systematic and methodical way.

2. **Detailed Preliminary Content**: Before addressing the main problem, the AI provides extensive preliminary content, including foundational concepts, relevant theories, and useful hints. This step ensures that all necessary background information is covered to understand and solve the problem.

3. **Step-by-Step Problem Solving**:
   
   - **Intermediate Questions**: The AI formulates a series of intermediate questions, each targeting a specific aspect of the complex problem. These questions guide the problem-solving process in a structured manner.
   
   - **Answer Sketches and Code Execution**: For each question, the AI develops a detailed answer sketch, which is then tested and refined through code execution. This process not only verifies the accuracy of the answer but also deepens the understanding of the problem.
   
   - **Detailed Answers**: Based on the code execution results, the AI provides comprehensive and detailed answers for each intermediate question, gradually building towards the solution of the original complex problem.

4. **Final Solution Presentation**:
   
   - **Solution Synthesis**: After addressing all intermediate questions, the AI synthesizes the findings into a complete solution for the original complex problem.
   
   - **Code for Final Solution**: The final solution is further verified or solved using coding, ensuring accuracy and precision.
   
   - **Formatted Final Answer**: The solution is presented in a clear, concise, and formally correct format, often using LaTeX for mathematical precision and enclosed within `\boxed{}` for emphasis.

### Application and Use Cases:

- **Ideal for Complex Mathematical Problems**: This approach is particularly effective for solving intricate mathematical problems that require a multi-step solution process.

- **Adaptability to Other Fields**: While primarily used for mathematics, the structure can be adapted to other fields like physics, engineering, and computer science, where complex problem-solving is required.

- **Educational Tool**: In an educational context, it can help students learn how to approach and solve complex problems step by step.

This version of Meta Prompting is designed to tackle problems that are too complex to be solved in a straightforward manner. It encourages a meticulous and methodical approach, ensuring that each aspect of the problem is thoroughly understood and addressed. The use of intermediate questions and detailed answer sketches, combined with code execution, makes it an effective strategy for deep and complex reasoning.



## Citations
Please cite the paper and star this repo if you use Meta Prompting (MP) and Cumulative Reasoning (CR) and find it interesting/useful, thanks! Feel free to contact zhangyif21@tsinghua.edu.cn | yangjq21@mails.tsinghua.edu.cn or open an issue if you have any questions.

```bibtex
@article{zhang2023meta,
  title={Meta Prompting for AGI Systems},
  author={Zhang, Yifan},
  journal={arXiv preprint arXiv:2311.11482},
  year={2023}
}

@article{zhang2023cumulative,
  title={Cumulative Reasoning With Large Language Models},
  author={Zhang, Yifan and Yang, Jingqin and Yuan, Yang and Yao, Andrew Chi-Chih},
  journal={arXiv preprint arXiv:2308.04371},
  year={2023}
}
```
