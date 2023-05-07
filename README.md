# 673-final 期末考猜題
## Sample Questions
1. Explain why microservices should have low coupling and high cohesion. 
- Low coupling ensures that microservices are loosely connected to each other, minimizing dependencies and allowing for faster, more flexible development and deployment.
- High cohesion ensures that microservices are highly focused on specific tasks or functions, making them easier to understand, test, and maintain over time.
- Low coupling and high cohesion together allow for greater scalability and adaptability in the microservices architecture, enabling teams to develop, test, and deploy individual services independently of each other.
- High cohesion also helps to reduce the risk of bugs and errors in the system, as each microservice has a clear purpose and set of responsibilities, making it easier to identify and fix issues.
- By focusing on low coupling and high cohesion, developers can create a more modular and extensible system, enabling the organization to quickly and easily add new features or services as needed.

- 這裡有五個要點解釋了為什麼微服務應該具有低耦合和高內聚性：

- 低耦合確保微服務彼此鬆散連接，最大限度地減少依賴性並允許更快、更靈活的開發和部署。
- 高內聚確保微服務高度專注於特定的任務或功能，使它們更容易理解、測試和維護。
- 低耦合和高內聚一起允許在微服務架構中具有更大的可擴展性和適應性，使團隊能夠開發、測試和部署彼此獨立的單個服務。
- 高內聚性還有助於降低系統中出現錯誤和錯誤的風險，因為每個微服務都有明確的目的和職責集，從而更容易識別和修復問題。
- 通過專注於低耦合和高內聚，開發人員可以創建更加模塊化和可擴展的系統，使組織能夠根據需要快速輕鬆地添加新功能或服務。


- Here is an example of how low coupling and high cohesion can be applied in a microservices architecture:

- Let's say a company is developing an e-commerce platform consisting of multiple microservices, including a product catalog service, a shopping cart service, a checkout service, and a payment service. To ensure low coupling and high cohesion:

- The product catalog service should be responsible for managing product data and related information, and should not have direct dependencies on the other services.
- The shopping cart service should be responsible for managing shopping cart data and related information, and should not have direct dependencies on the other services.
- The checkout service should be responsible for managing the checkout process, and should not have direct dependencies on the other services.
- The payment service should be responsible for processing payments, and should not have direct dependencies on the other services.
- Each service should have a well-defined API that enables communication with other services, and should adhere to standard protocols and interfaces.
- By designing each service with low coupling and high cohesion, the e-commerce platform can be more flexible, scalable, and maintainable over time. For example, the company could easily add new services or features to the platform without disrupting existing services, and could quickly update or replace individual services as needed.
以下是如何在微服務架構中應用低耦合和高內聚的示例：

- 假設一家公司正在開發一個由多個微服務組成的電子商務平台，包括產品目錄服務、購物車服務、結賬服務和支付服務。 為了保證低耦合和高內聚：

- 產品目錄服務應負責管理產品數據和相關信息，不應直接依賴於其他服務。
- 購物車服務應負責管理購物車數據和相關信息，不應直接依賴於其他服務。
- 結賬服務應負責管理結賬流程，不應直接依賴於其他服務。
- 支付服務應負責處理支付，不應直接依賴於其他服務。
- 每個服務都應該有一個定義良好的 API 來實現與其他服務的通信，並且應該遵守標準協議和接口。
- 通過以低耦合和高內聚的方式設計每個服務，電子商務平台可以隨著時間的推移變得更加靈活、可擴展和可維護。 例如，公司可以在不中斷現有服務的情況下輕鬆地向平台添加新服務或功能，並且可以根據需要快速更新或替換個別服務。
2. You are a software product manager for a company developing educational software products based around scientific simulations to be used by colleges. Explain why it is important to develop a product roadmap so that final product releases are available in the first three months of the year. 

- Developing a product roadmap for first quarter releases is important for timeliness, competitive advantage, and revenue generation.
- A product roadmap can help ensure that product releases are planned and executed efficiently, taking into account development, testing, and deployment timelines.
- 為第一季度發布製定產品路線圖對於及時性、競爭優勢和創收非常重要。
- 產品路線圖有助於確保產品發布得到有效規劃和執行，同時考慮開發、測試和部署時間表。
3. In the context of RESTful services, explain what is meant by a ‘resource’. How do RESTful services address resources and operate on them? 
- A resource in RESTful services is a unit of information or functionality that can be accessed and manipulated through a well-defined interface, typically identified using URIs.
- RESTful services operate on resources using HTTP methods, such as GET, POST, PUT, and DELETE, with each method having a specific purpose.
- GET is used to retrieve a representation of a resource, POST is used to create a new resource or perform a non-idempotent operation on an existing resource, PUT is used to update an existing resource or create a new resource if it does not exist, and DELETE is used to delete a resource.
- Clients send HTTP requests to a resource's URI using the appropriate HTTP method, and servers respond with an HTTP status code indicating the success or failure of the operation, along with a representation of the resource in a specified format.
- RESTful services are designed to be stateless, with each request containing all of the information necessary to complete the operation, enabling greater scalability and flexibility in the system.
- RESTful 服務中的資源是一個信息或功能單元，可以通過定義明確的接口訪問和操作，通常使用 URI 標識。
- RESTful 服務使用 HTTP 方法（例如 GET、POST、PUT 和 DELETE）對資源進行操作，每種方法都有特定的用途。
- GET 用於檢索資源的表示，POST 用於創建新資源或對現有資源執行非冪等操作，PUT 用於更新現有資源或創建新資源（如果不存在）， DELETE 用於刪除資源。
- 客戶端使用適當的 HTTP 方法向資源的 URI 發送 HTTP 請求，服務器以指示操作成功或失敗的 HTTP 狀態代碼以及指定格式的資源表示形式進行響應。
- RESTful 服務被設計為無狀態的，每個請求都包含完成操作所需的所有信息，從而使系統具有更大的可擴展性和靈活性。
##  Questions
### What is the difference between a monolithic and a microservices architecture?
- A monolithic architecture is a single, self-contained application, while a microservices architecture is composed of smaller, independent services.
- In a monolithic architecture, changes to one part of the application can affect other parts, while in a microservices architecture, each service can be updated and deployed independently.
- Monolithic architectures are typically easier to develop and deploy, while microservices architectures offer greater scalability and flexibility.
- Monolithic architectures can be more difficult to maintain over time, while microservices architectures require more infrastructure and management.
- Microservices architectures are often better suited for large, complex applications with many different services and components.
- 單體架構和微服務架構有什麼區別？
- 單體架構是一個獨立的應用程序，而微服務架構由更小的獨立服務組成。
- 在單體架構中，對應用程序的一部分進行更改會影響其他部分，而在微服務架構中，每個服務都可以獨立更新和部署。
- 單體架構通常更易於開發和部署，而微服務架構提供更大的可擴展性和靈活性。
- 隨著時間的推移，單體架構可能更難維護，而微服務架構需要更多的基礎設施和管理。
- 微服務架構通常更適合具有許多不同服務和組件的大型複雜應用程序。


### What is an API and why is it important for software development?
- An API (Application Programming Interface) is a set of protocols and standards that allow different software applications to communicate with each other.
- APIs are important for software development because they enable developers to create more modular, flexible applications that can be easily integrated with other systems.
- By providing a well-defined interface for interacting with an application, APIs allow developers to abstract away implementation details and focus on building higher-level functionality.
- APIs can also be used to expose data and functionality to external users and developers, enabling third-party integrations and partnerships.
- In modern software development, APIs are a critical component of many applications, from web and mobile apps to backend services and databases.
- 什麼是 API，為什麼它對軟件開發很重要？
- API（應用程序編程接口）是一組協議和標準，允許不同的軟件應用程序相互通信。
- API 對於軟件開發很重要，因為它們使開發人員能夠創建更模塊化、更靈活的應用程序，這些應用程序可以輕鬆地與其他系統集成。
- 通過提供與應用程序交互的定義良好的接口，API 允許開發人員抽像出實現細節並專注於構建更高級別的功能。
- API 還可用於向外部用戶和開發人員公開數據和功能，從而實現第三方集成和合作。
- 在現代軟件開發中，API 是許多應用程序的關鍵組件，從 Web 和移動應用程序到後端服務和數據庫。


### What is the role of containers in modern software development and deployment?
- Containers are a lightweight, portable way to package and deploy software applications and their dependencies.
- Containers provide a standardized environment for running applications, making it easier to deploy and manage them across different environments.
- Containers also enable greater scalability and flexibility, allowing applications to be quickly and easily deployed and scaled up or down as needed.
- Containerization can help reduce the risk of application conflicts and compatibility issues, by isolating applications and their dependencies from the underlying host system.
- In modern software development, containers are increasingly used in cloud environments and microservices architectures, as they provide a standardized, portable way to package and deploy individual services and components.
- 容器在現代軟件開發和部署中的作用是什麼？
- 容器是一種用於打包和部署軟件應用程序及其依賴項的輕量級、可移植方式。
- 容器為運行應用程序提供了一個標準化的環境，使得跨不同環境部署和管理它們變得更加容易。
- 容器還支持更大的可擴展性和靈活性，允許應用程序根據需要快速輕鬆地部署和擴展或縮減。
- 通過將應用程序及其依賴項與底層主機系統隔離開來，容器化有助於降低應用程序衝突和兼容性問題的風險。
- 在現代軟件開發中，容器越來越多地用於雲環境和微服務架構，因為它們提供了一種標準化、可移植的方式來打包和部署各個服務和組件。


### How do you ensure the security of a software application?
- Security should be built into the application from the outset, with a focus on identifying and mitigating potential risks and vulnerabilities.
- This may involve conducting regular security audits and penetration testing, and implementing strong authentication and access control mechanisms.
- Best practices for application security include using encryption to protect sensitive data, validating input and output to prevent injection attacks, and implementing secure coding practices.
- It is also important to stay up-to-date with the latest security threats and vulnerabilities, and to regularly update and patch software components to address known vulnerabilities.
- Security is a continuous process, and it is important to monitor and review application security on an ongoing basis, to ensure that it remains effective and up-to-date.
- 您如何確保軟件應用程序的安全性？
- 安全性應該從一開始就內置到應用程序中，重點是識別和減輕潛在的風險和漏洞。
- 這可能涉及定期進行安全審計和滲透測試，並實施強大的身份驗證和訪問控制機制。
- 應用程序安全的最佳實踐包括使用加密來保護敏感數據、驗證輸入和輸出以防止注入攻擊以及實施安全編碼實踐。
- 了解最新的安全威脅和漏洞並定期更新和修補軟件組件以解決已知漏洞也很重要。
- 安全是一個持續的過程，持續監控和審查應用程序安全性非常重要，以確保它保持有效和最新。


### What is the difference between unit testing and integration testing?
- Unit testing is the process of testing individual components or modules of an application in isolation, to ensure that they work as expected.
- Integration testing is the process of testing how different components of an application work together, to ensure that they integrate correctly and produce the desired outcome.
- Unit testing typically involves writing and executing automated tests that focus on a specific piece of functionality or code.
- Integration testing may involve manual testing, as well as automated tests, to ensure that different components and systems are integrated correctly and produce the desired outcome.
- Both unit testing and integration testing are important for ensuring the quality and reliability of software applications, and are typically conducted as part of a larger software testing and quality assurance process.
- 單元測試和集成測試有什麼區別？
- 單元測試是單獨測試應用程序的各個組件或模塊的過程，以確保它們按預期工作。
- 集成測試是測試應用程序的不同組件如何協同工作的過程，以確保它們正確集成並產生預期的結果。
- 單元測試通常涉及編寫和執行專注於特定功能或代碼的自動化測試。
- 集成測試可能涉及手動測試和自動測試，以確保正確集成不同的組件和系統並產生預期的結果。
- 單元測試和集成測試對於確保軟件應用程序的質量和可靠性都很重要，並且通常作為更大的軟件測試和質量保證過程的一部分進行。


### How do you optimize a web application for performance?
- Minimize HTTP requests by reducing the number of resources loaded on a page.
- Optimize images and other media to reduce their size and load time.
- Use a content delivery network (CDN) to distribute content and reduce server load.
- Use caching to store frequently accessed data and avoid repeated requests.
- Implement front-end optimization techniques, such as minification and compression, to reduce file sizes and load times.
- 如何優化 Web 應用程序的性能？
- 通過減少頁面上加載的資源數量來最小化 HTTP 請求。
- 優化圖像和其他媒體以減小它們的大小和加載時間。
- 使用內容分發網絡 (CDN) 分發內容並減少服務器負載。
- 使用緩存來存儲經常訪問的數據，避免重複請求。
- 實施前端優化技術，例如縮小和壓縮，以減少文件大小和加載時間。


### What is the role of DevOps in software development and deployment?
- DevOps is a software development methodology that emphasizes collaboration and communication between development and operations teams.
- The goal of DevOps is to increase the speed and efficiency of software development and deployment, by streamlining processes and automating tasks.
- DevOps practices include continuous integration and continuous deployment (CI/CD), automated testing, and infrastructure as code (IaC).
- By breaking down silos between development and operations teams, DevOps enables faster, more frequent releases and greater agility in responding to changing requirements.
- DevOps is increasingly important in modern software development, as businesses look to deliver software more quickly and efficiently in order to remain competitive.
- DevOps 在軟件開發和部署中的作用是什麼？
- DevOps 是一種軟件開發方法，強調開發和運營團隊之間的協作和溝通。
- DevOps 的目標是通過簡化流程和自動化任務來提高軟件開發和部署的速度和效率。
- DevOps 實踐包括持續集成和持續部署 (CI/CD)、自動化測試和基礎架構即代碼 (IaC)。
- 通過打破開發和運營團隊之間的孤島，DevOps 可以實現更快、更頻繁的發布和更大的敏捷性來響應不斷變化的需求。
- DevOps 在現代軟件開發中越來越重要，因為企業希望更快、更高效地交付軟件以保持競爭力。


### What is serverless computing and how does it differ from traditional server-based architectures?
- Serverless computing is a cloud computing model in which the cloud provider manages the infrastructure and resources needed to run an application, freeing developers from the need to manage servers and infrastructure themselves.
- Serverless computing differs from traditional server-based architectures in that developers only pay for the resources used by their application, rather than having to provision and manage servers and infrastructure themselves.
- Serverless computing enables greater scalability and flexibility, as applications can be quickly and easily scaled up or down as needed.
- However, serverless computing also introduces some challenges, such as increased complexity in managing multiple functions and services, and potential issues with vendor lock-in.
- Serverless computing is increasingly popular in modern software development, particularly for building cloud-native applications and microservices architectures.
- 什麼是無服務器計算，它與傳統的基於服務器的架構有何不同？
- 無服務器計算是一種雲計算模型，其中云提供商管理運行應用程序所需的基礎設施和資源，使開發人員無需自行管理服務器和基礎設施。
- 無服務器計算不同於傳統的基於服務器的架構，因為開發人員只需為其應用程序使用的資源付費，而不必自己配置和管理服務器和基礎設施。
- 無服務器計算可實現更大的可擴展性和靈活性，因為應用程序可以根據需要快速輕鬆地擴展或縮小。
- 然而，無服務器計算也帶來了一些挑戰，例如管理多個功能和服務的複雜性增加，以及供應商鎖定的潛在問題。
- 無服務器計算在現代軟件開發中越來越受歡迎，尤其是在構建雲原生應用程序和微服務架構方面。


### What is continuous integration and continuous deployment (CI/CD) and how do they relate to modern software development?
- Continuous integration (CI) is the practice of automatically building and testing code changes whenever they are committed to a version control system.
- Continuous deployment (CD) is the practice of automatically deploying code changes to production servers whenever they pass a set of automated tests and quality checks.
- Together, CI/CD enable fast, frequent releases and greater agility in responding to changing requirements.
- By automating the build, test, and deployment processes, CI/CD reduces the risk of errors and enables faster, more efficient software development and deployment.
- CI/CD is a core component of modern software development, particularly in agile and DevOps environments.
- 什麼是持續集成和持續部署 (CI/CD)，它們與現代軟件開發有何關係？
- 持續集成 (CI) 是在代碼更改提交到版本控制系統時自動構建和測試代碼更改的做法。
- 持續部署 (CD) 是一種在生產服務器通過一組自動化測試和質量檢查時自動將代碼更改部署到生產服務器的做法。
- CI/CD 共同支持快速、頻繁的發布和更大的敏捷性來響應不斷變化的需求。
- 通過自動化構建、測試和部署流程，CI/CD 降低了出錯風險，並實現了更快、更高效的軟件開發和部署。
- CI/CD 是現代軟件開發的核心組成部分，尤其是在敏捷和 DevOps 環境中。


### What are some common design patterns used in software development, and when should they be applied?
- The Singleton pattern is used to ensure that a class has only one instance and provide a global point of access to it.
- The Factory pattern is used to create objects of a specific type, without exposing the creation logic to the client.
- The Observer pattern is used to define a one-to-many relationship between objects, so that when one object changes state, all of its dependents are notified and updated automatically.
- The Adapter pattern is used to convert the interface of one class into the interface expected by a client, without changing the source code of either class.
The MVC (Model-View-Controller) pattern is used to separate the concerns of an application into three distinct components: the model (data and business logic), the view (user interface), and the controller (mediator between the model and view).
- 軟件開發中常用的設計模式有哪些，應該在什麼時候應用？
- 單例模式用於確保一個類只有一個實例並提供對其的全局訪問點。
- 工廠模式用於創建特定類型的對象，而不會將創建邏輯暴露給客戶端。
- 觀察者模式用於定義對象之間的一對多關係，這樣當一個對象改變狀態時，它的所有依賴對像都會收到通知並自動更新。
- Adapter 模式用於將一個類的接口轉換為客戶端期望的接口，而無需更改任何一個類的源代碼。
- MVC（模型-視圖-控制器）模式用於將應用程序的關注點分為三個不同的組件：模型（數據和業務邏輯）、視圖（用戶界面）和控制器（模型和視圖之間的中介） ).
### What is Agile software development, and how does it differ from traditional software development methodologies?
- Agile software development is an iterative, collaborative approach to software development that emphasizes flexibility and adaptability.
- Agile methodologies focus on delivering working software quickly and frequently, while also responding quickly to changing requirements and feedback.
- Agile teams typically work in short, time-boxed iterations (often called "sprints") and emphasize collaboration, communication, and self-organization.
- Agile methodologies differ from traditional software development methodologies, such as the Waterfall model, which emphasize sequential planning and - development phases and require a detailed plan upfront.
- 什麼是敏捷軟件開發，它與傳統軟件開發方法有何不同？
- 敏捷軟件開發是一種迭代的、協作的軟件開發方法，強調靈活性和適應性。
- 敏捷方法側重於快速、頻繁地交付工作軟件，同時快速響應不斷變化的需求和反饋。
- 敏捷團隊通常在短時間的、有時間限制的迭代（通常稱為“衝刺”）中工作，並強調協作、溝通和自組織。
- 敏捷方法不同於傳統的軟件開發方法，例如瀑布模型，它強調順序規劃和開發階段，並且需要預先制定詳細的計劃。


### What is Test-Driven Development (TDD), and how does it differ from traditional software testing methodologies?
- Test-Driven Development (TDD) is a software development methodology in which tests are written first, before any production code is written.
- TDD emphasizes writing small, focused tests that cover specific aspects of the application's functionality.
- TDD differs from traditional software testing methodologies, such as manual or automated testing, which typically occur after production code has been written.
- By writing tests first, TDD can help ensure that the code being written is focused on meeting specific requirements and that the tests provide comprehensive coverage of the application's functionality.
- TDD is increasingly popular in modern software development, particularly in agile and DevOps environments.
- 什麼是測試驅動開發 (TDD)，它與傳統的軟件測試方法有何不同？
- 測試驅動開發 (TDD) 是一種軟件開發方法，其中先編寫測試，然後再編寫任何生產代碼。
- TDD 強調編寫涵蓋應用程序功能的特定方面的小型、集中的測試。
- TDD 不同於傳統的軟件測試方法，例如手動或自動測試，後者通常發生在編寫生產代碼之後。
- 通過首先編寫測試，TDD 可以幫助確保編寫的代碼專注於滿足特定需求，並且測試可以全面覆蓋應用程序的功能。
- TDD 在現代軟件開發中越來越受歡迎，尤其是在敏捷和 DevOps 環境中。


### What is the role of machine learning in software development, and what are some common applications of machine learning in software development?
- Machine learning is a subfield of artificial intelligence (AI) that involves training computer algorithms to learn patterns in data and make predictions or decisions based on that data.
- Machine learning has many applications in software development, such as natural language processing, image recognition, and predictive analytics.
- In natural language processing, machine learning is used to enable chatbots and virtual assistants to understand and respond to human language.
- In image recognition, machine learning is used to enable applications to identify and classify images based on their contents.
- In predictive analytics, machine learning is used to analyze large datasets and identify patterns or trends that can be used to make predictions or inform business decisions.
- 機器學習在軟件開發中的作用是什麼，機器學習在軟件開發中有哪些常見應用？
- 機器學習是人工智能 (AI) 的一個子領域，涉及訓練計算機算法以學習數據中的模式並根據該數據做出預測或決策。
- 機器學習在軟件開發中有很多應用，例如自然語言處理、圖像識別和預測分析。
- 在自然語言處理中，機器學習用於使聊天機器人和虛擬助手能夠理解和響應人類語言。
- 在圖像識別中，機器學習用於使應用程序能夠根據圖像的內容對圖像進行識別和分類。
- 在預測分析中，機器學習用於分析大型數據集並識別可用於進行預測或通知業務決策的模式或趨勢。
### What is a software design pattern, and why are design patterns important in software development?
A software design pattern is a reusable solution to a common software development problem or challenge.
Design patterns provide a common language and set of best practices for software developers, helping to improve code quality and maintainability.
By using established design patterns, developers can save time and effort, as they do not need to invent new solutions to common problems.
Design patterns can also improve the scalability and flexibility of software applications, as they provide well-defined approaches to common problems.
Many popular software frameworks and libraries, such as Java's Spring framework, rely heavily on design patterns.
- 什麼是軟件設計模式，為什麼設計模式在軟件開發中很重要？
- 軟件設計模式是針對常見軟件開發問題或挑戰的可重用解決方案。
- 設計模式為軟件開發人員提供了一種通用語言和一組最佳實踐，有助於提高代碼質量和可維護性。
- 通過使用既定的設計模式，開發人員可以節省時間和精力，因為他們不需要為常見問題發明新的解決方案。
- 設計模式還可以提高軟件應用程序的可擴展性和靈活性，因為它們為常見問題提供了明確定義的方法。
- 許多流行的軟件框架和庫，例如 Java 的 Spring 框架，都嚴重依賴於設計模式。
### What is the role of documentation in software development, and what are some best practices for documenting software projects?
- Documentation plays an important role in software development, as it helps to ensure that software applications are maintainable and understandable over time.
- Good documentation should be clear, concise, and up-to-date, and should include information on how the software works, how to install and configure it, and how to use it.
- Some best practices for documenting software projects include using a consistent format and style, including code samples and examples where appropriate, and providing both high-level and detailed documentation.
- Documentation should be kept up-to-date over time, and should be reviewed and updated regularly to ensure accuracy and relevance.
- Many popular software documentation tools and platforms, such as Sphinx and Read the Docs, are available to help streamline the documentation process.
- 文檔在軟件開發中的作用是什麼？記錄軟件項目的一些最佳實踐是什麼？
- 文檔在軟件開發中起著重要作用，因為它有助於確保軟件應用程序隨著時間的推移是可維護和可理解的。
- 好的文檔應該清晰、簡明和最新，並且應該包括有關軟件如何工作、如何安裝和配置以及如何使用它的信息。
- 記錄軟件項目的一些最佳實踐包括使用一致的格式和風格，包括適當的代碼示例和示例，並提供高級和詳細的文檔。
- 文件應隨著時間的推移保持最新，並應定期審查和更新以確保准確性和相關性。
- 許多流行的軟件文檔工具和平台（例如 Sphinx 和 Read the Docs）都可用於幫助簡化文檔編制過程。
### What is a software framework, and how does it differ from a library?
- A software framework is a pre-existing set of libraries, tools, and conventions that provide a structure for building software applications.
- Frameworks typically provide a set of standard functions, methods, and interfaces that developers can use to build their applications, without needing to write everything from scratch.
- Frameworks differ from libraries in that they provide a more comprehensive set of tools and conventions, whereas libraries typically provide more specific, focused functionality.
- Examples of popular software frameworks include Ruby on Rails, Django, and AngularJS.
- 什麼是軟件框架，它與庫有何不同？
- 軟件框架是一組預先存在的庫、工具和約定，它們提供了用於構建軟件應用程序的結構。
- 框架通常提供一組標準函數、方法和接口，開發人員可以使用這些函數、方法和接口來構建他們的應用程序，而無需從頭開始編寫所有內容。
- 框架與庫的不同之處在於它們提供了一組更全面的工具和約定，而庫通常提供更具體、更有針對性的功能。
- 流行軟件框架的示例包括 Ruby on Rails、Django 和 AngularJS。


### What is version control, and why is it important in software development?
- Version control is a system for tracking changes to software code over time, enabling developers to collaborate and manage code changes more effectively.
- Version control systems enable developers to track changes to individual files and keep a history of all changes made to the codebase over time.
- By using version control, developers can work collaboratively on a single codebase, without risking conflicts or overwriting each other's changes.
- Version control also provides a backup of the codebase and enables developers to easily roll back to previous versions if necessary.
- Popular version control systems include Git, Subversion, and Mercurial.
- 什麼是版本控制，為什麼它在軟件開發中很重要？
- 版本控制是一種用於跟踪軟件代碼隨時間變化的系統，使開發人員能夠更有效地協作和管理代碼更改。
- 版本控制系統使開發人員能夠跟踪對單個文件的更改，並保留隨時間推移對代碼庫所做的所有更改的歷史記錄。
- 通過使用版本控制，開發人員可以在單個代碼庫上協同工作，而不會冒衝突或覆蓋彼此更改的風險。
- 版本控制還提供了代碼庫的備份，使開發人員能夠在必要時輕鬆回滾到以前的版本。
- 流行的版本控制系統包括 Git、Subversion 和 Mercurial。
## What is a software bug, and how can they be prevented or mitigated?
- A software bug is an error or flaw in a software application that causes it to behave in unexpected or unintended ways.
- Bugs can be caused by a variety of factors, such as programming errors, incorrect assumptions, or changes to the underlying system or environment.
- To prevent or mitigate bugs, developers can use a variety of techniques, such as automated testing, code reviews, and debugging tools.
- Best practices for bug prevention and mitigation include writing clean, well-documented code, conducting regular code reviews, and using automated testing tools and techniques.
- When bugs do occur, it is important to identify and fix them as quickly as possible, in order to avoid negative impact on users and business operations.
- 什麼是軟件錯誤，如何預防或減輕它們？
- 軟件錯誤是軟件應用程序中的錯誤或缺陷，會導致其以意想不到或無意的方式運行。
- 錯誤可能由多種因素引起，例如編程錯誤、不正確的假設或底層系統或環境的更改。
- 為了防止或減少錯誤，開發人員可以使用各種技術，例如自動測試、代碼審查和調試工具。
- 錯誤預防和緩解的最佳實踐包括編寫乾淨、文檔齊全的代碼、進行定期代碼審查以及使用自動化測試工具和技術。
- 當錯誤確實發生時，重要的是盡快識別並修復它們，以避免對用戶和業務運營產生負面影響。


### What is a software API, and how can they be designed effectively?
- A software API (Application Programming Interface) is a set of protocols, tools, and standards that enable different software applications to communicate with each other.
- APIs can be designed effectively by following a set of best practices, such as using consistent naming conventions and data structures, providing clear and concise documentation, and following RESTful principles for web APIs.
- APIs should also be designed with scalability and flexibility in mind, allowing for changes and updates to be made without disrupting existing integrations.
- Security and access control should also be considered when designing APIs, to ensure that only authorized users and applications are able to access sensitive data or functionality.
- Effective API design can help to promote interoperability and enable integrations with third-party applications, while also improving the overall quality and maintainability of software applications.
- 什麼是軟件 API，如何有效地設計它們？
- 軟件 API（應用程序編程接口）是一組協議、工具和標準，使不同的軟件應用程序能夠相互通信。
- 可以通過遵循一組最佳實踐來有效地設計 API，例如使用一致的命名約定和數據結構，提供清晰簡潔的文檔，以及遵循 Web API 的 RESTful 原則。
- API 的設計還應考慮可擴展性和靈活性，允許在不中斷現有集成的情況下進行更改和更新。
- 設計 API 時還應考慮安全性和訪問控制，以確保只有授權用戶和應用程序才能訪問敏感數據或功能。
- 有效的 API 設計有助於促進互操作性並實現與第三方應用程序的集成，同時還可以提高軟件應用程序的整體質量和可維護性。


### What is DevSecOps, and how does it differ from traditional approaches to software development and security?
- DevSecOps is an approach to software development and operations that emphasizes the integration of security into all aspects of the development process.
- DevSecOps differs from traditional approaches to software development and security, which often treat security as an afterthought or separate process.
- DevSecOps promotes a culture of shared responsibility for security, with developers, operations teams, and security teams working together to identify and mitigate security risks throughout the development process.
- To implement DevSecOps effectively, organizations may need to adopt new tools and processes, such as automated security testing, vulnerability scanning, and code analysis.
- DevSecOps is increasingly important in modern software development, particularly in industries such as finance, healthcare, and government, where security and compliance are critical concerns.
- 什麼是 DevSecOps，它與傳統的軟件開發和安全方法有何不同？
- DevSecOps 是一種軟件開發和運營方法，強調將安全性集成到開發過程的各個方面。
- DevSecOps 不同於傳統的軟件開發和安全方法，後者通常將安全視為事後考慮或單獨的過程。
- DevSecOps 提倡一種共同承擔安全責任的文化，開發人員、運營團隊和安全團隊共同努力，在整個開發過程中識別和減輕安全風險。
- 為了有效實施 DevSecOps，組織可能需要採用新的工具和流程，例如自動化安全測試、漏洞掃描和代碼分析。
- DevSecOps 在現代軟件開發中越來越重要，特別是在金融、醫療保健和政府等行業，在這些行業中，安全性和合規性是關鍵問題。


### What is a container, and how does it differ from a virtual machine?
- A container is a lightweight, portable environment for running software applications, which packages all of the necessary code and dependencies together in a single, self-contained unit.
- Containers differ from virtual machines in that they do not require a separate operating system to run, and share the host system's kernel and resources.
- Containers enable greater portability and scalability than traditional software development approaches, as applications can be easily deployed and run in different environments and architectures.
- Popular containerization platforms include Docker and Kubernetes.
- 什麼是容器，它與虛擬機有何不同？
- 容器是用於運行軟件應用程序的輕型、可移植環境，它將所有必需的代碼和依賴項打包在一個獨立的單元中。
- 容器不同於虛擬機，因為它們不需要單獨的操作系統來運行，並且共享主機系統的內核和資源。
- 與傳統的軟件開發方法相比，容器具有更高的可移植性和可擴展性，因為應用程序可以在不同的環境和架構中輕鬆部署和運行。
- 流行的容器化平台包括 Docker 和 Kubernetes。


### What is cloud computing, and how does it differ from traditional on-premise infrastructure?
- Cloud computing is a model of computing in which software applications and services are hosted and run on remote servers, accessed over the internet.
- Cloud computing differs from traditional on-premise infrastructure in that it enables greater scalability, flexibility, and accessibility, as applications and services can be easily scaled up or down as needed, without requiring additional hardware or infrastructure.
- Cloud computing also enables organizations to reduce costs and increase efficiency, as they only pay for the resources and services they need, rather than investing in costly hardware and infrastructure upfront.
- Popular cloud computing platforms include Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform.
- 雲計算是一種計算模型，其中軟件應用程序和服務在遠程服務器上託管和運行，並通過 Internet 訪問。
- 雲計算不同於傳統的本地基礎設施，因為它支持更大的可擴展性、靈活性和可訪問性，因為應用程序和服務可以根據需要輕鬆擴展或縮減，而無需額外的硬件或基礎設施。
- 雲計算還使組織能夠降低成本並提高效率，因為他們只需為所需的資源和服務付費，而不是預先投資昂貴的硬件和基礎設施。
- 流行的雲計算平台包括亞馬遜網絡服務 (AWS)、微軟 Azure 和谷歌云平台。


### What is Big Data, and how can it be used in software development?
- Big Data refers to large, complex datasets that are difficult to process and analyze using traditional data processing techniques.
- Big Data can be used in software development to enable more advanced data analytics and insights, such as predictive analytics and machine learning.
- To work with Big Data effectively, developers may need to use specialized tools and techniques, such as Hadoop or Spark, to process and analyze large datasets.
- Big Data can also enable new applications and use cases, such as real-time data processing and analysis, and can be used to inform business decisions and strategies.
- However, working with Big Data also introduces some challenges, such as managing data security and privacy, and ensuring that data is stored and processed in compliance with relevant regulations.
- 什麼是大數據，它如何用於軟件開發？
- 大數據是指難以使用傳統數據處理技術進行處理和分析的龐大、複雜的數據集。
- 大數據可用於軟件開發，以實現更高級的數據分析和洞察力，例如預測分析和機器學習。
- 為了有效地使用大數據，開發人員可能需要使用專門的工具和技術（例如 Hadoop 或 Spark）來處理和分析大型數據集。
- 大數據還可以啟用新的應用程序和用例，例如實時數據處理和分析，並可用於為業務決策和戰略提供信息。
- 然而，使用大數據也帶來了一些挑戰，例如管理數據安全和隱私，以及確保數據的存儲和處理符合相關法規。


### What is user experience (UX) design, and why is it important in software development?
- User experience (UX) design is the process of designing software applications that are easy to use, intuitive, and enjoyable for users.
- UX design is important in software development because it can significantly impact user satisfaction, adoption, and retention.
- Effective UX design requires a deep understanding of user needs and behaviors, as well as knowledge of design principles and best practices.
- UX design involves a variety of techniques, such as user research, wireframing, prototyping, and usability testing.
- UX design should be an iterative process, with continuous feedback and testing to ensure that the software application meets user needs and expectations.
- 什麼是用戶體驗 (UX) 設計，為什麼它在軟件開發中很重要？
- 用戶體驗 (UX) 設計是為用戶設計易於使用、直觀且令人愉悅的軟件應用程序的過程。
- UX 設計在軟件開發中很重要，因為它可以顯著影響用戶滿意度、採用率和保留率。
- 有效的用戶體驗設計需要深入了解用戶需求和行為，以及設計原則和最佳實踐的知識。
- 用戶體驗設計涉及多種技術，例如用戶研究、線框圖、原型設計和可用性測試。
- UX 設計應該是一個迭代的過程，通過持續的反饋和測試來確保軟件應用程序滿足用戶的需求和期望。


## lecture 1
### Product Manager
- Product management is a complex discipline that requires multiple skills to master.
- A framework for effective product management consists of six core knowledge areas and six supporting ones.
- The six core areas are vision and leadership, product life cycle management, product strategy and market research, business model and financials, product roadmap, and user experience and product backlog.
- The supporting areas are general market knowledge, development/technologies, marketing, sales and support, project/release management, and process.
- Effective product management requires establishing a shared vision, setting realistic goals, managing stakeholders, actively listening, negotiating, and making tough product decisions.
- It also involves understanding the product life cycle, identifying target users and customers, segmenting the market, performing competitor analysis, and positioning the product.
- The financial aspect of product management involves understanding business goals, describing how the product's value proposition is monetized, creating a financial forecast or business case, and working with colleagues from the finance department.
- Creating a product roadmap requires formulating realistic product goals, metrics and key performance indicators, release dates or timeframes, and key features. It also involves formulating a go-to-market strategy and understanding when the roadmap should be reviewed and changed.
Delivering a great user experience involves describing the desired user experience, creating scenarios, epics, user stories, storyboards, workflow diagrams, and storymaps, prioritizing and managing the product backlog, and selecting sprint goals.
- The supporting knowledge areas involve understanding current customers and users, software technologies, marketing channels, sales channels, project/release management, and ideation and innovation processes.
- The framework can be used to define specific product roles and identify gaps in product knowledge, as well as to determine learning measures for individuals or groups of product managers or product owners.

## lecture 2
### Agile
- Agile development is a widely adopted methodology in software development.
- However, many projects claiming to be Agile may not be truly Agile.
- Agile is a mindset for software development, not just a process or toolbox.
- People and interactions should be valued over processes and tools.
- Agile recognizes change as inevitable and provides meetings to manage it.
- Self-organizing teams are effective teams, and practices cannot be imposed on a team.
- Work should be done as late as possible, and success cannot be easily replicated in software development.
- Respect for people is important, and communication is key.
- The Agile mindset complements Agile processes and practices.
- Agile processes and practices should be seen as a toolbox to pick from as needed, not a rigid set of rules.
### Scrum
- Scrum is an Agile framework for managing and completing complex projects.
- It was originally developed for software development projects, but can be applied to any project where flexibility and adaptability are required.
- The framework consists of three main roles: the Product Owner, the Scrum Master, and the Development Team.
- The Product Owner is responsible for creating and maintaining the product backlog, a prioritized list of features or tasks that need to be completed.
- The Scrum Master is responsible for facilitating the Scrum process and ensuring that the team is following the framework.
- The Development Team is responsible for delivering a potentially releasable product increment at the end of each sprint.
- Sprints are fixed-length iterations of one to four weeks, during which the team works to complete a set of items from the product backlog.
- Each sprint begins with a sprint planning meeting, where the team plans what work they will complete during the sprint.
- Daily scrum meetings are held to provide updates on progress and identify any obstacles or issues that need to be addressed.
- At the end of each sprint, the team holds a sprint review to demonstrate the completed work to stakeholders and receive feedback.
- The sprint ends with a sprint retrospective, where the team reflects on the sprint and identifies areas for improvement.
- Scrum emphasizes self-organizing teams, with team members collaborating and taking ownership of their work.
- The framework is designed to be flexible and adaptable, with the team able to adjust their approach based on feedback and changing circumstances.
- Scrum can be combined with other Agile methodologies, such as Kanban or Extreme Programming (XP), to create a hybrid approach.
- To successfully implement Scrum, it is important to have buy-in from all team members and stakeholders, and to have a clear understanding of the framework and its principles.
### CI/CD
## lecture 3
### feature driven
- Feature-Driven Development (FDD) is an agile process designed to work for larger projects and teams.
- FDD was invented by Jeff De Luca and is often overlooked in the agile software development community.
- FDD uses "just enough" upfront activities to support additional communication needed in larger projects/teams.
- FDD organizes projects around five processes, the first three of which are equivalent to iteration zero activities.
- The first process involves creating a domain object model in collaboration with domain experts to establish a shared vocabulary.
- The second process involves building a features list, which is organized into a three-level hierarchy based on domain subject areas and business activities.
- The third process involves constructing an initial schedule, assigning responsibilities to Chief Programmers, and establishing individual class ownership.
- FDD does not use the term "iteration zero," but instead calls the initial processes "initial project-wide activities."
- FDD's upfront activities are not about big design upfront (BDUF), but about doing "Just Enough Design Initially" (JEDI).
- Experienced object modelers and development/project managers guide the modeling and planning teams in FDD.
https://dzone.com/articles/introduction-feature-driven
### persona
- A persona is a way to model, summarize, and communicate research about people who have been observed or researched in some way.
Each persona represents a significant portion of people in the real world and enables the designer to focus on a manageable and memorable cast of characters.
- A persona document should clearly communicate and summarize research data, but the document itself is not the most important thing. The fundamental understanding of users is what’s important.
- Alan Cooper informally developed personas in the early ’80s as a way to empathize with and internalize the mindset of people who would eventually use the software he was designing.
- Personas are an essential part of goal-directed design, which combines new and old methodologies from ethnography, market research, and strategic planning to simultaneously address business needs, technological requirements, and user goals.
- Personas are never used in isolation, but rather are implemented in conjunction with other processes, concepts, and methods that support and augment their use.
### user story
## lecture 4
### architectural style
#### client/server architectural style:

Client/server architecture involves a separate client and server system connected by a network.
The simplest form is a 2-Tier architecture, where a server application is accessed directly by multiple clients.
Historically, client/server architecture referred to a graphical desktop UI application that communicated with a database server or dedicated file server.
Today, examples of the client/server architectural style include web browser-based programs, Microsoft Windows operating system-based applications, and tools and utilities that manipulate remote systems.
Other variations on the client/server style include client-queue-client systems, peer-to-peer applications, and application servers.
Benefits of the client/server architectural style include higher security, centralized data access, and ease of maintenance.
The client/server architectural style is suitable for applications that are server-based and support many clients, web-based applications, business processes used by people throughout an organization, and services for other applications to consume.
The traditional 2-Tier client/server architectural style has several disadvantages, such as close combination of application data and business logic on the server and dependence on a central server.
To address these issues, the client/server architectural style has evolved into the more general 3-Tier (or N-Tier) architectural style, which provides additional benefits.
#### Client/Server:

Involves a separate client and server system with a connecting network
Client initiates one or more requests and waits for replies from the server
Examples include web-based programs, Microsoft Windows-based applications, and tools that manipulate remote systems
Benefits include higher security, centralized data access, and ease of maintenance
Disadvantages include closely combined application data and business logic, and dependence on a central server
#### N-Tier/3-Tier:

Segments functionality into tiers that can be located on physically separate computers
Each tier is independent of all other tiers except for those immediately above and below it
At least three separate logical parts, each responsible for specific functionality
Benefits include maintainability, scalability, flexibility, and availability
Consider using if processing requirements of layers differ, or security requirements of layers differ
Object-Oriented:

Based on the division of responsibilities into individual reusable and self-sufficient objects
Views a system as a series of cooperating objects instead of a set of routines or procedural instructions
Key principles include abstraction, composition, inheritance, encapsulation, polymorphism, and decoupling
Benefits include understandability, reusability, testability, extensibility, and high cohesion
Consider using if you want to model your application based on real world objects and actions, or you have complex business logic that requires abstraction and dynamic behavior
#### Service-Oriented:

Enables application functionality to be provided as a set of services, and the creation of applications that make use of software services
Services are loosely coupled and use standards-based interfaces that can be invoked, published, and discovered
Key principles include autonomy, distributability, loose coupling, shared schema and contract, and compatibility based on policy
Benefits include domain alignment, abstraction, discoverability, interoperability, and rationalization
Consider using if you have access to suitable services that you wish to reuse, want to build applications that compose a variety of services into a single UI, or are creating cloud-based applications.    


 https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ee658117(v=pandp.10)
## lecture 5

## lecture 10
### microservice architecture 
- The microservice architecture is a design approach for structuring applications as a set of independently deployable, loosely coupled services, each consisting of one or more subdomains.
- Each subdomain implements a slice of business functionality, including business logic and adapters for communicating with the outside world.
- Teams are organized into small, cross-functional groups responsible for one or more subdomains.
- Distributed operations are implemented using synchronous or asynchronous protocols, such as HTTP/REST or message brokers like Apache Kafka.
- The benefits of the microservice architecture include simple services, team autonomy, fast deployment pipeline, support for multiple technology stacks, and segregation of subdomains by characteristics to improve scalability, availability, and security.
- The potential drawbacks include complex and inefficient interactions, complex eventually consistent transactions, runtime coupling between services, and tight design-time coupling.
- Service collaboration patterns, such as Saga and CQRS, are used to implement distributed operations that span multiple services and ensure loose coupling.
- There are many related patterns and approaches to the microservice architecture, including messaging and remote procedure invocation patterns, database per service, API gateway, client-side and server-side discovery, testing patterns, circuit breaker, observability patterns, UI patterns, and - cross-cutting concerns patterns.
- Companies like Netflix, Amazon, and eBay have all adopted the microservice architecture to scale their applications and improve agility.  
https://microservices.io/patterns/microservices.html

## lecture 11
### software testing
software testing mentioned in the article:

#### Unit tests:

White-box tests that focus on a small, limited scope (usually a single function)
Written by the software developer to ensure code paths and edge cases are covered
Typically short and quickly written, with carefully chosen test parameters
Mock objects are commonly used to isolate the function under test
Ideally written before the function(s) they test, following Test Driven Development principles
#### Integration tests:

Grey-box tests that focus on interactions between objects and interfaces on a limited scope
Written by the software developer to ensure objects/subsystems interact with dependencies correctly
Medium-length and quickly written, typically checking success/failure states and inputs/outputs
Mocking dependencies, shared resources, and IPC is common practice
Ideally written before the object(s) they test, following TDD principles
#### Acceptance tests:

Black-box tests that cover how a user moves through the system on a broader scope
Written by the product owner, client, tester, or developer to ensure client requirements are met
Short and written by outlining the steps the user must take to complete requested functionality
Ideally written by the client or product owner before the UI is developed
Key technologies include manual tests, the Gherkin domain-specific language, and visual regression tools
#### Refinement tests:

Black-box tests that determine if a proposed UI is useful, usable, aesthetically pleasing, identifiable, inspirational, and valuable
Typically written by a designer or UX expert by presenting a UI design to users and gathering data on how they experience it
Beginning refinement testing before any real (non-prototype) code is implemented often reduces the number of design/UI changes later in development
Key technologies include visual difference tools, A/B testing frameworks, and accessibility testing
Other names include UX tests, usability tests, and end-user tests
#### System tests:

Black-box tests that cover the system as a whole on an extremely broad scope
Written by the tester, developer, and product owner to catch regressions, set performance thresholds, and stress-test the system
Results aren't always a strict pass/fail, trends are more important
Ideally written or their parameters chosen before any development work is done
Key technologies include analysis tools and load-testing tools.  


https://archive.openconcept.ca//blog/mparker/overview-software-testing
### code review
code review:

Review small chunks of code at a time, ideally no more than 400 lines of code, to ensure thoroughness and reduce the chance of missing defects.
Take your time during the review process and aim for a pace of 500 lines of code or fewer per hour, as this has been shown to be the most effective rate for finding defects.
Use checklists to ensure that common mistakes are caught and that all aspects of the code are reviewed.
Establish a process for fixing defects found during the review process, such as using a collaborative code review tool that allows reviewers to log bugs and discuss changes with the author.
Foster a positive code review culture by emphasizing collaboration and learning rather than using defects found in reviews as a basis for evaluating team members.   

https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/

