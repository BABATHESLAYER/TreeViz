# Firebase Studio
https://github.com/user-attachments/assets/4271349e-0d3c-4ade-9221-f33258ef1c02

<img width="1919" height="874" alt="image" src="https://github.com/user-attachments/assets/265bf608-d56c-41a3-a16a-493c8d637380" />

This is a NextJS starter in Firebase Studio.

To get started, take a look at src/app/page.tsx.

Project Overview: TreeViz
TreeViz is an interactive web-based educational tool designed to visualize complex Tree data structures and their traversal algorithms in real-time. By bridging the gap between abstract code and visual representation, it simplifies the learning process for one of the most challenging topics in Computer Science.

Key Features
Dynamic Tree Construction:
Users can input a custom array (as seen in the "Tree Definition" box) to build a Binary Tree or Binary Search Tree (BST) instantly. The tool automatically handles the positioning of nodes to create a clean, readable layout.

Step-by-Step Algorithm Execution:
The tool focuses on Non-Recursive (Iterative) Traversal, which is often harder for students to grasp than recursive methods. The visualizer plays through the algorithm, highlighting the current node being processed.

Real-time Stack Visualization:
A standout feature is the Stack panel. Since iterative traversals use a stack to keep track of nodes, TreeViz shows nodes being pushed and popped from the stack in sync with the tree animation. This provides a clear "under-the-hood" look at how the memory is being managed.

Integrated Pseudocode:
The interface includes a dedicated section for pseudocode. As the animation progresses, it highlights the specific line of code being executed, helping users map logic to visual actions.

Playback Controls:
Equipped with standard media controls (Play, Pause, Step-forward, Reset), the tool allows learners to study the traversal at their own pace.

Technical Implementation
Frontend: Built with modern web technologies (React/JavaScript) to ensure a responsive and smooth user interface.

State Management: Uses state to track the progress of the traversal, the current stack contents, and the list of "Visited Nodes" in real-time.

Visualization Logic: Implements custom drawing logic to render the tree connections and node highlights dynamically based on the user's input.

Use Cases
Classroom Learning: A perfect tool for professors to demonstrate how iterative Inorder, Preorder, or Postorder traversals function.

Interview Preparation: Helps candidates visualize how stacks are used to replace recursion, a common topic in technical interviews.

Debugging Logic: Developers can use the custom input feature to visualize specific edge cases in tree structures.




