# 🤖 **Artificial Intelligence Systems**  

[中文版本](./README_cn.md)  

This course, titled **Artificial Intelligence Systems**, explores the design of computer systems that support artificial intelligence. The English equivalent title is **Systems for AI**. Throughout the course, we interchangeably use the terms **Artificial Intelligence Systems**, **AI-Systems**, and **Systems for AI**.

This course is part of the [Microsoft AI Education and Open Collaboration Community](https://github.com/microsoft/ai-edu) under the [Foundational Tutorials](https://github.com/microsoft/ai-edu/tree/master/%E5%9F%BA%E7%A1%80%E6%95%99%E7%A8%8B/) module, identified as *A6 - Artificial Intelligence Systems*.  

📌 **Explore more content:** [Microsoft AI Education and Open Collaboration Community](https://github.com/microsoft/ai-edu).  

---

## 🎯 **Course Objectives**  

This course aims to:  

1. Provide a comprehensive understanding of computer system architectures that support deep learning and teach the system design lifecycle through real-world problems.  
2. Introduce cutting-edge research in **AI for Systems** and **Systems for AI**, helping students identify and define meaningful research challenges.  
3. Develop hands-on skills through experiments that involve implementing and optimizing system modules using mainstream frameworks, platforms, and tools.  

**Prerequisites:**  
- Programming: C/C++/Python  
- Computer Architecture  
- Algorithms  

---

## 📖 **Course Outline**  

### **[Lecture Modules](./Lectures)**  

#### **Foundational Lectures**  

| Lecture No. | Topic                            | Highlights                                                                                     |
|-------------|----------------------------------|-----------------------------------------------------------------------------------------------|
| 1           | Course Introduction              | Overview and basics of systems and AI                                                        |
| 2           | Overview of AI Systems           | History of AI systems, neural network fundamentals, basics of AI systems                     |
| 3           | Deep Neural Network Frameworks   | Backpropagation, tensors, computation graphs <br> Systems: PyTorch, TensorFlow              |
| 4           | Matrix Operations and Architectures | Matrix ops, CPU/SIMD, GPGPU, ASIC/TPU <br> Systems: BLAS, TPU                                 |
| 5           | Distributed Training Algorithms  | Data parallelism, model parallelism, distributed SGD <br> Systems: PipeDream                 |
| 6           | Distributed Training Systems     | MPI, parameter servers, RDMA <br> Systems: Horovod                                           |
| 7           | Cluster Scheduling and Resource Management | Running DNN tasks on clusters, containers, resource allocation, scheduling <br> Systems: Kubeflow, Gandiva |
| 8           | Deep Learning Inference Systems | Efficiency, latency, throughput <br> Systems: TensorRT, ONNX                                 |

#### **Advanced Lectures**  

| Lecture No. | Topic                            | Highlights                                                                                     |
|-------------|----------------------------------|-----------------------------------------------------------------------------------------------|
| 9           | Compiling and Optimizing Computation Graphs | IR, pattern matching, memory optimization <br> Systems: TVM, MLIR                            |
| 10          | Neural Network Compression       | Model compression, pruning, sparsity optimization                                             |
| 11          | Automated Machine Learning Systems | Hyperparameter tuning, NAS <br> Systems: AutoKeras, NNI                                       |
| 12          | Reinforcement Learning Systems   | RL theory and systems <br> Systems: AlphaZero, RLlib                                          |
| 13          | Security and Privacy             | Federated learning, privacy-preserving AI <br> Systems: DeepFake                              |
| 14          | AI for Optimizing Systems        | AI in traditional systems: streaming, database indexing, resource scheduling                 |

---

### **[Laboratory Modules](./Labs)**  

#### **Basic Labs**  

| Lab No. | Title                               | Description                                                                                   |
|---------|-------------------------------------|-----------------------------------------------------------------------------------------------|
| 1       | Framework and Tool Basics          | Hands-on exploration of key tools and frameworks                                             |
| 2       | Custom Tensor Operations           | Develop a new tensor operation                                                               |
| 3       | CUDA Implementation and Optimization | Design and optimize CUDA operations                                                          |
| 4       | AllReduce Implementation           | Build or optimize AllReduce functionality                                                    |
| 5       | Cloud Training and Inference Setup | Set up containers for cloud-based AI tasks                                                   |

#### **Advanced Labs**  

| Lab No. | Title                               | Description                                                                                   |
|---------|-------------------------------------|-----------------------------------------------------------------------------------------------|
| 6       | Learning Scheduler Management      | Explore scheduling systems for AI tasks                                                      |
| 7       | Distributed Training Practices     | Work on distributed training tasks                                                           |
| 8       | Automated ML System Practice       | Hands-on AutoML experience                                                                   |
| 9       | Reinforcement Learning System      | Design and optimize RL systems                                                               |

---

## 📚 **Course Materials**  

The **Artificial Intelligence Systems** course material is part of the [Microsoft AI Education and Open Collaboration Community](https://github.com/microsoft/ai-edu). The textbook includes a structured and holistic approach to AI system education.  

📖 **Textbook:** [Deep Learning System Design: Theory and Practice](Textbook/README.md)  

<div align="center">
<img src="imgs/Book.jpg" alt="Deep Learning System Design: Theory and Practice" height="300"/>
</div>  

---

## 🤝 **Contributing**  

Contributions are welcome!  

1. Fork the repository.  
2. Create a feature branch:  
   ```bash
   git checkout -b feature-name
   ```  
3. Commit and push changes:  
   ```bash
   git push origin feature-name
   ```  
4. Submit a Pull Request.  

This project adopts the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).  

---

## 🛡️ **Legal Notices**  

Microsoft and contributors license the content under the [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/legalcode) license. Code is licensed under the [MIT License](https://opensource.org/licenses/MIT).  

--- 

Let me know if you’d like additional adjustments! 😊
