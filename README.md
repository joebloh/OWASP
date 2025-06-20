1. **LLM Security verification standard 0.0.1**  
   1. Secure Config and Maintenance   
      1. Ensure LLMs, hosted by a model provider or self-hosted, are configured and maintained securely to prevent unauthorized access and leakage of sensitive info  
   2. Model LifeCycle   
      1. Ensure ML lifecycle for models used within LLM-powered systems considers dataset curation, model training, validation  
   3. Real Time Learning  
      1. Reduce the risk associated with real time learning within LLM systems, where models are continuously fine-tuned based on user interactions in real time  
   4. Model Memory and Storage  
      1. Mechanisms which allow for “memory” or addition knowledge that was not included in the training phase is safely handled   
   5. Secure LLM Integration  
      1. Establish controls that enable safe interactions and operations between application components and LLM’s   
   6. Agents and plugins  
      1. Autonomous nature of agent-based systems presents new risks and can increase the impact of attacks  
   7. Dependency control  
      1. Third party components and dependencies are safely handled to reduce supply chain  
   8. Monitor and Anomaly detection  
      1. Continuously monitor the use of LLM-powered applications to detect anomalous

2. **LLM and GenAI Security Center of excellence guide**  
   1. COE Considerations  
   2. Working group roles and responsibilities   
      1. Builders  
      2. Operators  
   3. Example Implementation Phases and Timelines  
      1. Planning and Setup  
      2. Integration and Development   
      3. Operationalization  
      4. Evaluate and Expansion  
      5. Emerging Threats

3. **LLM and GenAI security solutions landscape guide 2025**  
   1. Defining the Security Solutions Landscape   
      1. Application Types and Scope: Which impact the people, process, and tools need based on complexity of application and LLM Env, as-a-service, self-hosted, or custom-built  
         2. Emerging LLLSecOps Process: Shifting Ecosystem  
         3. Threat and Risk Modeling: Understanding the risk posed by LLM systems  
         4. Tracking emerging solutions: Updating   
      2. LLM Application Categories, Security Challenges  
         1. Static Prompt Augmentation  
            1. Key Characteristics   
               1. Human to Model/Model to Human RR  
               2. Static Prompt Augmentation  
               3. Flexible and Creative  
               4. Simple and Accessible   
               5. Rapid Prototyping and Experimentation  
            2. Use Cases  
               1. Content Generation  
               2. Text Summarization  
               3. Q/A systems  
               4. Language translation  
               5. Virtual Assistants/Chat bot  
            3. Challenges   
               1. Inconsistent response, bias, compliance risk  
         2. Agentic Applications  
            1. Key Characteristics   
               1. Autonomy and Decision Making  
               2. Interaction with External Systems  
               3. Statemangment and Memory  
               4. Complex workflow automation  
               5. Human-agent collaboration  
            2. Use Cases  
               1. Virtual Assistants  
               2. Customer Support  
               3. Process Automation Agent  
               4. Data Analyst and Reporting Agent  
               5. Intelligent Personalization   
               6. Security and Compliance   
            3. Challenges  
               1. Unauthorized access, exploiting multiple systems,   
         3. LLM Plug-ins, Extensions  
            1. Key Characteristics  
               1. Modular and Flexible  
               2. Seamless Integration  
               3. Task Specific Focus  
               4. Ease of Deployment and Use  
               5. Rapid Updates and Maintenance  
            2. Use Case  
               1. Content Generation Tools  
               2. Text Summary Tools  
            3. Challenges  
               1. Plugins interacting with sensitive data must be vetted, software/cloud capability issues, access  
         4. Complex Applications  
            1. Key Characteristics  
               1. Multi-component architectures are designed to process prompts from other non-human systems  
               2. Often use multiple integrations, including other Models  
               3. Scalability and Performance  
               4. Advanced Features and Customization  
               5. End-to-End Workflow systems  
            2. Use Cases  
               1. Legal Document Analysis  
               2. Automated Financial Reporting Systems  
               3.  Customer Service Platforms  
               4. Healthcare Diagnostics   
            3. Challenges  
               1. Major\!  
      3. LLM Development and Consumption Models  
      4. LLMOps and LLMSecOps Defined   
         1. Scoping/Planning  
         2. Application Development and Experimentation  
         3. Test and Evaluate  
         4. Release  
         5. Deploy  
         6. Operate  
         7. Monitor  
         8. Govern  
   2. OWASP Top 10 for LLM Solutions Landscape  
      1. Emerging GenAI/LLM-Specific Security Solutions  
         1. LLM Firewall: is a security layer specifically for LLM to protect from unauthorized access, malicious inputs, harmful outputs  
         2. LLM Automated Benchmarking: tools for identifying weaknesses unique to LLM’s  
         3. LLM Guard Rails: protective mechanisms to operate in ethical, legal and functional boundaries  
         4. AI Security Posture Management: AI-SPM cover entire AI LifeCycle to ensure Models are resilient, trustworthy, and compliant with industry standards  
      2. LLM and Generative AI Security Solutions  
      3. Landscape Solution Matrix  
         1. Libraries in Manua  
            1. Scoping/Planning  
            2. Data Augmentation and Fine-Tuning  
            3. Development and Experimentation  
            4. Test and Evaluation  
            5. Release  
            6. Deploy  
            7. Operate  
            8. Monitor  

4. **OWASP Top 10 for LLM Applications 2025**  
   1. LLM01: Prompt Injection : User prompts alter LLM’s  
      1. Types  
         1. Direct Injection  
         2. Indirect Injection  
      2. Prevention and Mitigation Strategies  
         1. Constrain Model Behavior   
         2. Define and Validate expected output formats   
         3. Implement input and output filtering   
         4. Enforce privilege control and least privilege access  
         5. Require human approval for high-risk actions  
         6. Segregate and identify external content   
         7. Conduct adversarial testing and attack simulations  
      3. Examples  
         1. Direct injection  
         2. Indirect injection  
         3. Unintentional injection  
         4. Intentional Model Influence  
         5. Code Injection  
         6. Payload Splitting   
         7. Multimodal injection   
         8. Adversarial Suffix  
         9. Multilingual/Obfuscated Attack  
   2. LLM02: Sensitive Information Disclosure: PII, Legal, HIPPA, Gov  
      1. Types  
         1. PII Leakage  
         2. Proprietary Algorithm Exposure  
         3. Sensitive Business Data Disclosure  
      2. Prevention and Mitigation Strategies  
         1. Sanitation  
            1. Integrate Data Sanitization Techniques  
            2. Robust Input Validation  
         2. Access Controls  
            1. Enforce Strict Access Control  
            2. Restrict Data Sources  
         3. Federated Learning and Privacy Techniques  
            1. Utilize Federated Learning   
            2. Incorporate Differential Privacy   
         4. User Education and Transparency   
            1. Educate Users  
            2. Ensure Transparency  
         5. Secure System Configuration  
            1. Conceal System Preamble  
            2. Ref Security Misconfig Best Practices  
         6. Advanced Techniques  
            1. Homomorphic Encryption  
            2. Tokenization and Redaction  
      3. Example Attack Scenarios   
         1. Unintentional Data Exposure  
         2. Targeted Prompt Injection  
         3. Data Leak via Training Data    
   3. LLM03: Supply Chain: Third Party   
      1. Types  
         1. Traditional Third-Party package Vulnerabilities   
         2. Licensing Risks  
         3. Outdated or Deprecated Models  
         4. Vulnerable Pre-Trained Model  
         5. Weak Model Provenance   
         6. Vulnerable LoRa adapters   
         7. Exploit Collaborative Development Process  
         8. LLM Model On Device supply-chain vulnerabilities   
         9. Unclear T\&C and Data Privacy Policies  
      2. Prevention and Mitigation Strategies  
         1. ?  
      3. Sample Attack Scenarios   
         1. Vulnerable Python Library  
         2. Direct Tampering  
         3. Finetuning Popular Model  
         4. Pre-Trained Models  
         5. Compromised Third-Party Supplier   
         6. Supplier Infiltration  
         7. CloudBourne and CloudJacking Attacks  
         8. Leftovers  
         9. WizardLM  
         10. Model Merge/Format Conversion Service   
         11. Reverse engineer mobile app  
         12. Dataset Poisoning  
         13. T\&C and Privacy Policy    
   4. LLM04: Data and Model Poisoning: Pre-training/Fine-tuning/Embedding Data is manipulated  
      1. Types  
         1. Malice user introduce poison data at training for bias output   
         2.  Inject harmful data directly into training  
         3. Introducing sensitive or proprietary info during interaction  
         4. Unverified training data  
         5. Lack of access restrictions introducing unsafe data  
      2. Prevention and Mitigation Strategies  
         1. Track Data origins and transformations  
         2. Vet Data vendors rigorously   
         3. Implement strict sandboxing  
         4. Tailor Models for different use cases  
         5. Ensure Infrastructure Controls  
         6. Use Data Version Control (DVC)  
         7. Store User-Supplied Data in Vector Databases  
         8. Red-Teaming  
         9. Monitor loss and Model behavior   
         10. Reduce Hallucinations with RAG  
      3. Sample Attack Scenarios  
         1. Biases with manipulated training data  
         2. Toxic Data  
         3. False Documents  
         4. Inadequate Filtering  
         5. Poison Data with a Backdoor Trigger  
   5. LLM05: Improper Output Handling  
      1. Types  
         1. LLM output entered directly into a shell or exe. for remote code execution  
         2.  JavaScript or Markdown generated by LLM leading to XSS  
         3. LLM SQL generated queries  
         4. LLM output to create file paths for traversal attacks  
         5. LLM generated Email content  
      2. Prevention and Mitigation Strategies  
         1. Treat Models as users. Zero-Trust approach  
         2. Follow OWASP ASVS  
         3. Encode model output   
         4. Implement context-aware output  
         5. Used parameterized or prepared statements for all DB operations  
         6. Strict CSP   
         7. Robust logging and monitoring  
      3. Attack Scenarios   
         1. LLM Chatbot leaks privileges of Admin or higher roles  
         2. Scrap or capture conversation or webpage data, to encode and transmit  
         3. Allows users to generate LLM SQL. Delete table etc.  
         4. Generate webpage content bypassing output sanitization.   
         5. Generate dynamic email templates  
         6. Code generation risks  
   6. LLM06: Excessive Agency  
      1. Types:  
         1. Excessive Functionality  
         2. Excessive Permission  
         3. Excessive Autonomy  
      2. Prevention and Mitigation Strategies:  
         1. Minimize Extensions  
         2. Minimize Extension Functionality  
         3. Avoid Open-Ended Extensions  
         4. Minimize Extension permissions  
         5. Execute Extensions in User’s Context  
         6. Require User Approval  
         7. Complete Mediation  
         8. Sanitize Inputs and Outputs  
      3. Attack Scenarios:  
         1. An LLM-based agent is granted access to an email mailbox to summarize messages. However that agent has functions to send messages too. A malicious incoming email tricks the LLM to scan the mailbox and forward sensitive information.  
   7. LLM07: System Prompt Leakage  
      1. Types:  
         1. Exposure of Sensitive Functionality  
         2. Exposure to Internal Rules  
         3. Revealing of Filtering Criteria  
         4. Disclosure of Permissions and User Roles   
      2. Prevention and Mitigation Strategies:  
         1. Separate Sensitive Data from System Prompts  
         2. Avoid Reliance on System Prompts for Strict Behavior Control  
         3. Implement Guardrails  
         4. Ensure Security Controls are Enforced Independently of LLM  
      3. Attack Scenarios:  
         1. An LLM has a system prompt that contains credentials  
         2. An LLM has a system prompt that prohibits the generation of offensive content, external links, and code execution. An attacker extracts the prompt and then can bypass those instructions  
   8. LLM08: Vector and Embedding Weaknesses   
      1. Types:  
         1. Unauthorized Access and Data Leakage  
         2. Cross-Context Information leaks and Federation Knowledge Conflict  
         3. Embedding Inversion Attacks  
         4. Data Poisoning Attacks  
         5. Behavior Alteration  
      2. Prevention and Mitigation Strategies:  
         1. Permissions and Access Control  
         2. Data Validation and Source Authentication  
         3. Data review for Combination and classification  
         4. Monitor and Logging  
      3. Attack Scenarios:  
         1. Data Poisoning   
         2. Access Control and Data Leakage risk by combining Data with Different Access Restrictions   
         3. Behavior Alteration of the Foundational Model   
   9. LLM09: Misinformation  
      1. Types:  
         1. Factual inaccuracies   
         2. Unsupported Claims  
         3. Misrepresentation of Expertise  
         4. Unsafe Code Generation   
      2. Prevention and Mitigation Strategies:  
         1. Retrieval-Augmented Generation  
         2. Model Fine-Tuning  
         3. Cross-Validation and Human Oversight  
         4. Automated Validation Mechanisms  
         5. Risk Communication  
         6. Secure Coding Practices  
         7. User Interface Design  
         8. Training and Education  
      3. Attack Scenarios:  
         1. Find common hallucinations and publish malicious packages with those names to widely used repositories. Then Developers implement the code suggested by the agent.  
         2. A Medical Company chatbot provides poor information leading to harmful consequences   
   10. LLM10: Unbound Consumption  
       1. Types:  
          1. Variable-Length Input Flood  
          2. Denial of Wallet  
          3. Continuous Input Overflow  
          4. Resource Intensive Queries  
          5. Model Extraction via API  
       2. Prevention and Mitigation Strategies:  
          1. Input Validation  
          2. Limit Exposure of Logits and Logprobes  
          3. Rate Limiting  
          4. Resource Allocations Management  
          5. Timeouts and Throttling  
          6. Sandbox Techniques  
          7. Comprehensive Logging, Monitoring and Abnormality Detection  
          8. Watermarking  
          9. Graceful Degradation  
          10. Limited Queued Actions and Scale Robustly  
          11. Adversarial Robustness Training  
          12. Glitch Token Filtering  
          13. Access Controls  
          14. Centralized ML Model Inventory  
          15. Automated MLOps Deployment  
       3. Attack Scenarios:  
          1. Uncontrolled Input Size  
          2. Repeated Requests  
          3. Resource-Intensive Queries   
          4. Denial of Wallet  
          5. Functional Model Replication  
          6. Bypassing System Input Filtering
