[Domain 1](#domain1-top) **Security and Risk Management**

[1.1](#1.1) Understand, adhere to, and promote professional ethics
As a CISSP, you must understand and follow the (ISC)² code of ethics, as well as your organization’s own code.

- (ISC)² Code of Professional Ethics. Take the time to read the code of ethics available at www.isc2.org/Ethics. At a
minimum, know and understand the ethics canons:

  - Protect society, the common good, necessary public trust and confidence, and the infrastructure.
This is “do the right thing.” Put the common good ahead of yourself. Ensure that the public can have faith
in your infrastructure and security.

  - Act honorably, honestly, justly, responsibly, and legally. Always follow the laws. But what if you find
yourself working on a project where conflicting laws from different countries or jurisdictions apply? In such
a case, you should prioritize the local jurisdiction from which you are performing the services.

  - Provide diligent and competent service to principles. Avoid passing yourself as an expert or as qualified
in areas that you aren’t. Maintain and expand your skills to provide competent services.

  - Advance and protect the profession. Don’t bring negative publicity to the profession. Provide competent
services, get training and act honorably. Think of it like this: If you follow the first three canons in the code
of ethics, you automatically comply with this one.

- Organizational code of ethics. You must also support ethics at your organization. This can be interpreted to mean
evangelizing ethics throughout the organization, providing documentation and training around ethics, or looking
for ways to enhance the existing organizational ethics. Some organizations might have slightly different ethics than
others, so be sure to familiarize yourself with your organization’s ethics and guidelines.

[1.2](#1.2) Understand and apply security concepts
- **Confidentiality**:
  - Concept of measures used to ensure the protection of the secrecy of data, objects, and resources
  - Confidentiality protections prevent disclosure while protecting authorized access
  - Preserving authorized restrictions on information access and disclosure, including the means for protecting personal privacy and prioprietary information
  - Sensitive data, including personally identifiable information (PII) must be kept confidential. Confidentiality is different from secrecy
  - Preserving confidentiality means protecting an asset or data, even if it's not a secret
  
- **Integrity**:
  - Concept of protecting the reliability and correctness of data. Integrity protection prevents unauthorized alterations of data
  - Preventing unauthorized subjects from making modifications
  - Preventing authorized subjects from making unauthorized modifications, such as mistakes
  - Maintaining the internal and external consistency of objects

- **Availability**:
  - Authorized subjects are granted timely and uninterrupted access to objects
  - To ensure high availability of services and data, use techniques like failover clustering, site resiliency,
automatic failover, load balancing, redundancy of hardware and software components, and fault tolerance

- **Authenticity**: ensuring a transmission, message or sender is legitimate. See the NIST glossary for examples: https://csrc.nist.gov/glossary/term/authenticity

- **Nonrepudiation**: 
  - ensures that the subject of activity or who caused an event cannot deny that the event occurred
  - Nonrepudiation is made possible through identification, authentication, authorization, accountability, and auditing

- **AAA Services**:
  - Identification: claiming to be an identity when attempting to access a secured area or system
  - Authentication: proving that you are that claimed identity
  - Authorization: defining the permissions (i.e. allow/grant and/or deny) of a resource and object access for a specific identity or subject
  - Auditing: recording a log of the events and activities related to the system and subjects
  - Accounting: (aka accountability) is reviewing log files to check for compliance and violations in order to hold subjects accountable for their actions, especially violations of organizational security policy
 
 [1.3](#1.3) **Evaluate and apply security governance principles**
 
- **Security governance**: the collection of practices related to supporting, evaluating, defining, and directing the security efforts of an organization. 
  - security governance is the implementation of a security solution and a management method that are tightly interconnected
  - There are numerous security frameworks and governance guidelines, including the National Institute of Standards and Technology (NIST) SP 800-53 and NIST SP 800-100
- **The security function**: the aspect of operating a business that focuses on the task of evaluating and improving security over time. To manage security, an org must implement proper and sufficient security governance
  - the act of performing a risk assessment to drive the security policy is the clearest and most direct example of management of the security function
- **Alignment of Security Function to Business Strategy, Goals, Mission, and Objectives**
  - **Strategic Plan**: a strategic plan is a long-term plan (useful for 5 years). It defines the organization's security purpose. A strategic plan should include risk assessment.
  - **Tactical Plan**: mid-term plan (1 year or less) developed to provide more details on accomplishing the goals set forth in the strategic plan
  - **Operational Plan**: a short-term, highly detailed plan based on strategic or tactical plans
  - All of these — strategy, goals, missions, and objectives — flow down, with each one supporting the others.
Objectives are the closest to the ground and represent small efforts to help you achieve a mission. Missions
represent a collection of objectives, and one or more missions leads to goals. When you reach your goals, you are
achieving the strategy
  - A security framework must closely tie to mission and objectives,enabling the business to complete its objectives and advance the mission while securing the environment based on risk tolerance
- **Organizational Processes**
  -  Security governance should address every aspect of an organization, including organizational processes of acquisitions, divestitures, and governance
  -  Be aware of the risks in acquisitions (since the state of the IT environment to be integrated is unknown, due diligence is key) and divestitures (how to split the IT infrastructure and what to do with identities and credentials)
  -  Understand the value of governance committees (vendor governance, project governance, architecture governance, etc.)
  -  Executives,managers and appointed individuals meet to review architecture, projects and incidents (security or otherwise),and provide approvals for new strategies or directions. The goal is a fresh set of eyes, often eyes that are not purely focused on information security
  - When evaluating a third-party for your security integration, consider the following:
    - on-site assement
    - document exchange and review
    - process/policy review
    - third-party audit

- **Organizational Roles and Responsibilities**
  -  Senior Manager: has a responsibility to keep the business running and to maximize profits and shareholder value
  - Security Professional: has the functional responsibility for security, including writing the security policy and implementing it
  - Asset Owner: responsible for classifying information for placement or protection within the security solution
  - Custodian: responsible for the task of implementing the proscribed protection defined by the security policy and senior management
  - Auditor: responsible for reviewing and verifying that the security policy is properly implemented

- **Security control frameworks**
  - A control framework helps ensure that your organization is covering all the bases around securing the environment. There are many frameworks to choose from, such as:
    -  Control Objectives for Information Technology (COBIT)
      - COBIT is a documented set of best IT security practices by ISACA
      - Six key principles:
        - Provide stakeholder value
        - Holistic approach
        - Dynamic governance system
        - Governance distinct from management
        - Tailored to enterprise needs
        - End-to-end governance system   
    -  ISO 27000 series (27000, 27001, 27002, etc.). 
    -  NIST CyberSecurity Framework (CSF)
      - designed for commerical orgs and critical infrastructure, consisting of five functions:
        - identify
        - protect
        - detect
        - respond
        - recovery    
  - Due care/due diligence
    - Due diligence is establishing a plan, policy, and process to protect the interests of the organization. Due diligence is about understanding your security governance principles (policies and procedures) and the risks to your organization. Due diligence often involves gathering information through discovery, risk assessments and review of existing documentation; developing a formalized security structure containing a security policy, standards, baselines guidlines, and procedures; documentation to establish written policies; and disseminating the information to the organization
    - Due care is practicing the individual activities that maintain the due diligence effort. Due care is about your legal responsibility within the law or within organizational policies to implement your organization’s controls, follow security policies, do the right thing and make reasonable choices
    - Security documentation is the security policy
    - After establishing a framework for governance, security awareness training should be implemented, including all new hires, who complete the security awareness training as they come on board, and existing employees who should recertify regularly (typically yearly).

[1.4](#1.4) **Determine compliance and other requirements**
- Understand the difference between criminal, civil, and administrative law.
  - Criminal law: protects society against acts that violate the basic principles we believe in. Violations of criminal law are prosectued by federal and state governments
  - Civil law: provides the framework for the transaction of business between people and organizations. Violations of civil law are brought to the court and argued by the two affected parties
  - Administrative law is used by government agencies to effectively carry out their day-to-day business
- Compliance: Organizations may find themselves subject to a wide variety of laws, and regulations imposed by regulatory agencies or contractual obligation
  -  Payment Card Industry Data Security Standard (PCI DSS) - governs the security of credit card information and is enforced through the terms of a merchant agreement between a business that accpets CC payments, and the bank that processes the business' transactions
  -  Sarbanes-Oxley (SOX) - financial systems may be audited to ensure security controls are sufficient to ensure compliance with SOX
  -  Gramm-Leach-Bliley Act (GLBA) - affects banks, insurance companies, and credit providers; included a number of limitations on the types of information that could be exchanged even among subsidiaries of the same corp, and required financial institutions to provide written privacy policies to all their customers
  -  Health Insurance Portability and Accountability Act (HIPAA) - privacy and security regulations requiring strict security measures for hospitals, physicians, insurance companies, and other organizations that process or store private medical information about individuals; also clearly defines the rights of individuals who are the subject of medical records and requires organizations that maintain such records to disclose these rights in writing
  -  Federal Information Security Management Act (FISMA), requires federal agencies to implement an information security program that covers the agency's operations and contractors
  -  Computer Fraud and Abuse Act (CFAA) (as amended) protects computers used by the government or in interstate commerce from a variety of abuses
  -  Electronic Communications Privacy Act (ECPA) makes it a crime to invade the electronic privacy of an individual
  -  Digital Millennium Copyright Act prohibits the circumvention of copyright protection mechanisms placed in digital media and limits the liability of internet service providers for the activities of their users
-  Privacy requirements
  - European Union's General Data Protection Regulation (GDPR) - replaced Data Protection Directive (DPD), purpose is to provide a single, harmonized law that covers data throughout the EU
    - Lawfulness, fairness, and transparency
    - Purpose Limitation
    - Data Minimization
    - Accuracy
    - Storage Limitation
    - Security
    - Accountability
  - California Consumer Privacy Act (CCPA)
  - Be familiar with the EU Data Protection Directive. Be familiar with the requirements around healthcare
data, credit card data and other PII data as it relates to various countries and their laws and regulations

[1.5](#1.5) **Understand legal and regulatory issues that pertain to information security in a holistic context**
  - Cybercrime and data breaches:
    - Understand the notification requirements placed on organizations that experience a data breach
    - California's SB 1386 implemented the first statewide requiremnt to notify individuals of a breach of their personnel information; all other states eventually followed suit with similar laws
    - Currently, federal law only requires notification of individuals when a HIPAA-covered entity breaches their protected health information
    - Before an organization expands to other countries, perform due diligence to understand legal systems and what changes might be required to the way that data is handled and secured
    - In particular, be familiar with:
      - Council of Europe Convention on Cybercrime, a treaty signed by many countries that establishes standards for cybercrime policy 
      - laws about data breaches, including notification requirements. 
      - In the US, the Health Information Technology for Economic and Clinical Health (HITECH) Act requires notification of a data breach in some cases, such as when the personal health information was not protected as required by the Health Insurance Portability and Accountability Act (HIPAA) law 
      - The Gramm-Leach-Bliley Act (GLBA) applies to insurance and financial organizations; it requires notification to federal regulators, law enforcement agencies and customers when a data breach occurs. 
      - Certain states also impose their own requirements concerning data breaches 
      - the EU and other countries have their own requirements, for instance, the GDPR has very strict data breach notification requirements: A data breach must be reported to the competent supervisory authority within 72 hours of its discovery
      - Some countries do not have any reporting requirements
  - Licensing and intellectual property (IP) requirements
    - Trademarks:words, slogans, and logos used to identify a company and its products or services
    - Patents:A temporary monopoly for producing a specific item such as a toy, which must be novel and unique to qualify for a patent
      - Utility: protect the intellectual property rights of inventors
      - Design: cover the appearance of an invention and last for 15 years. They don't protect the idea of an invention only its form, and are generally seen as weaker
      - Software: area of on-going controversy; Google vs Oracle; given to rise of "patent trolls"
    - Copyright: exclusive use of artistic, musical or literary works which prevents unauthorized duplication, distribution or modification
    - Licensing: a contract between the software producer and the consumer which limits the use and/or distribution of the software
    - Trade Secrets: intellectual property that is critical to a business, and significant damage would result if it were disclosed to competitors or the public
  - Import / Export controls:
    -  Every country has laws around the import and export of hardware and software. For example, the US has restrictions around the export of cryptographic technology, and Russia requires a license to import encryption technologies manufactured outside the country
  -  Transborder data flow: 
    - Organizations should adhere to origin country-specific laws and regulations, regardless of where data resides
    - Also be aware of applicable laws where data is stored and systems are used
  - Privacy:
    -  Many laws include privacy protections for personal data. The EU’s General Data Protection Regulation (GDPR) has strong privacy rules that apply to any organization anywhere that stores or processes the personal data of EU residents; these individuals must be told how their data is collected and used, and they must be able to opt out. 
    -  The privacy guidelines of the Organization for Economic Co-operation and Development (OECD) require organizations to avoid unjustified obstacles to trans-border data flow, set limits to personal data collection, protect personal data with reasonable security and more. 
    -  The EU-US Privacy Shield (formerly the EU-US Safe Harbor agreement) controls data flow from the EU to the United States. The EU has more stringent privacy protections and without the Privacy Shield, personal data flow from the EU to the United States would not be allowed

[1.6](#1.6) **Understand requirements for investigation types (i.e. administrative, criminal, civil, regulatory, industry standards)**