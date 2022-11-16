# DEVELOPER'S GUIDE TO THE DIFFERENCES BETWEEN CERAMIC AND COMPOSE DB

This is a comprehensive tutorial to help you understand the differences between Ceramic and Compose DB.

## What you will Learn…

In this tutorial, you will learn

1. Introduction to Ceramic
2. Reasons you should Build with Ceramic
3. Ceramic’s Unique Features and Use Cases
4. Introduction to ComposeDB
5. Why build with ComposeDB?
6. The differences between Ceramic and ComposeDB

> **N.B:** For clarification of terms, check out Ceramic's glossary [<u>_here_</u>](https://developers.ceramic.network/reference/glossary/).

# Introduction to Ceramic

![Ceramic Logo](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/Ceramic.png?raw=true)

Ceramic is a decentralized data network that enables application developers easily build apps with composable Web3 data which can be reused across applications - making them interoperable.

Ceramic comprises a generalized data protocol where data is owned and modifiable only by its owner with global data availability, speedy data query, and multi-chain data operability across applications.

## **Why should you Build with Ceramic?**

Ceramic provides developers with a marketplace of decentralized data models which can be easily plugged into their applications.

The Ceramic data network comprises a wide collection of unique features that make data usage, query, storage and interoperability scalable.

## **Ceramic Unique Features and Use Cases**

No doubt, Ceramic provides developers with vast options.

So let's take a look at some of the cool features you as a developer can leverage;🚀

1. Data Composability
2. Multi-chain Web3 Sign-in & Identity
3. Decentralized User Reputation
4. Interoperable Social Graphs
5. Ceramic's High-level SDK

### 1. **Data Composability**

![Compsable-Data](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/Composable-Data.jpg?raw=true)

> Image Src: [Accenture.com](https://insuranceblog.accenture.com)

With trends like decentralized social media, decentralized blogs and decentralized reputation platforms taking off recently, data composability, mutability and usability are very important to understand.

Ceramic stores data in models which can be retrieved and reused by different applications. A data model refers to application features like following, posts, user profiles, etc.

Unlike in web 2 where these data are built as data silos (i.e. stored in a spot and cannot be transferred), ceramic enables interoperable systems and applications to solve this challenge.

### 2. **Multi-Chain Web3 Sign-in Identity**

![Multi-Chain Wallet Sign in](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/Multi-Chain-Sign-In.png?raw=true)

Signing in with web3 is great, but a multi-chain way to do the same and authenticate is even better.

By implementing Ceramic in your applications, you can utilize Ceramic's decentralized identifier (DID) - a standard for user accounts, compatible with all blockchain wallets.

With DID, data is tied up to a user's decentralized identity (instead of a smart contract or off-chain solution).

This means users control their data and can verify with any blockchain wallet of their choice.

### 3. **Decentralized Reputation**

![Decentralized Reputation](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/Decentralized-Reputations.png?raw=true)

> Image Src: [Blockchain: A Question of Reputation](https://miro.medium.com)

What we presently have (in web2) is a system whereby reputation systems (i.e. posts, user profiles, etc) are heavily centralized.

For instance, users cannot transfer their reputation on LinkedIn to Facebook This is because reputation is stored in centralized data silos which cannot communicate with each other.

Web3 developers and application builders can leverage Ceramic's data protocol to enable users to access applications from different blockchains, connects their multiple wallets to a single DID, and more importantly, carry their reputation around with them across different blockchain ecosystems.

### 4. **Interoperable Social Graphs**

Just like with the reputation systems, social graphs (like the Instagram following, LinkedIn connections, YouTube subscribers, etc) are stored in isolation. And a random app developer cannot query Facebook/Twitter/LinkedIn's social graph.

This is what Ceramic seeks to change!

By leveraging Ceramic's standardized data models, Web3 developers can enable users to move their social graph to whatever ecosystem they desire.

### 5. **Ceramic's High-level SDK**

Web3 developers can build with Ceramic's low-level and high-level libraries.

For complex applications, developers can build with lower-level HTTP clients, which provides them with a Ceramic node that they can run locally.

Also, for less complex applications, developers can work with Ceramic's easy-to-use high-level SDK - Self.ID.

Self.ID is a single, high-level framework that enables dApp developers to build user data-centric and composable data applications.

Self.ID provides full access to the Ceramic data network which simplifies the process of retrieving and updating data linked to a 3ID(Three ID).

> **N.B:** 3ID is one of Ceramic's approaches to decentralized identities.

# Introduction to ComposeDB

![ComposeDB](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/ComposeDB.png?raw=true)

ComposeDB on ceramic is a decentralized composable graph database that provides a **graph structure** for interacting with data on the Ceramic network.

ComposeDB enables developers to build decentralized applications on Ceramic network, thereby enjoying the ability to retrieve, store, update, modify, and reuse composable Web3 data models leveraging GraphQL.

> For an overview of ComposeDB check out [<u>_this documentation_</u>](https://composedb.js.org/docs/0.3.x/introduction).

## **Why Build with ComposeDB?**

ComposeDB supports common development needs by providing Libraries (for complex cases) and sets of CLI commands (for more basic uses). This gives developers access to rich data models and interoperable data within the Ceramic network.

Also, ComposeDB allows developers to define and query complex graph database schemas. Thus making indexing and querying a possibility on Ceramic.

> To uncover ComposeDB's salient features check out [<u>_this article_</u>](https://blog.ceramic.network/composedb-using-ceramic-as-a-graph-database/#:~:text=Overview%20of%20ComposeDB,overview%20of%20concepts.).

## **The Differences Between Ceramic and ComposeDB**

![Ceramic vs ComposeDB Image](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/CeramicXDB.png?raw=true)

Although Ceramic and ComposeDB both aim at achieving the same goal (i.e. a decentralized data ecosystem), the operational quo architectural framework powering both systems are quite dissimilar.

This is worthy of note, especially for Web3 developers.

As a developer, an understanding of the differences between Ceramic and ComposeDB is best achieved by looking at both under their underlying concepts.

1. Database Type
2. Data Query
3. Network Client
4. Accounts Method
5. Indexing
6. Authentication Mechanisms
7. Data Model Reusability & Composability
8. User Experience
9. Developer Experience

![The Differences Between Ceramic and ComposeDB](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/TheDifferences.jpg?raw=true)

> Source: [<u>ComposeDB: Using Ceramic as a Graph Database</u>](https://blog.ceramic.network/composedb-using-ceramic-as-a-graph-database)

### 1. **Database Type**

![SQL Database Image](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/SQL-Database.png?raw=true)

With ComposeDB, documents are stored using a model in a local database to provide fast access and query capabilities. Nodes on ComposeDB will be backed by a SQL database, which will be used to index and construct the database for data models in your composite.

These nodes independently index, store data and update the database based on the models available in its composite.

This is quite different from what we currently have in Ceramic, which operates a key-value store.

### 2. **Data Query**

The ComposeDB architecture saves the hassle that comes with development. Developers building with ComposeDB needs just one library - **the ComposeDB client**.

The ComposeDB client provides a graphical interface to the Ceramic network, which needs to be passed a composite to saturate its APIs and identify the data model you are working with.

The only requirement needed when working with ComposeDB is integrating your ComposeDB clients with your composite.

Once this is done, you gain complete access to the Ceramic network and can start sending queries and mutations against your Ceramic node.

Building with ComposeDB is more optimized than setting up your application directly with Ceramic’s developer packages, which involves having to deal with several JS library method calls (such as DID data store, etc).

### 3. **Network Client**

![Network Client Image](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/Internet-Clients-Server-2.png?raw=true)

There are several different gateways to access the Ceramic data network. This gateway is referred to as a **client** - responsible for providing developers interfaces to a Ceramic node.

Clients open the doorways to user authentication, stream-type provision, and interfaces for loading and querying streams. The present Ceramic network clients include HTTP clients, JS Core clients, Model Manager, and Self.ID SDK, amongst others.

Compose DB, with the focus of efficiently streamlining the ceramic network, simply allows HTTP clients and GraphQL clients.

### 4. **Accounts Method**

Accounts, in Ceramic, are user entities that can own streams (i.e. individual data on the ceramic network) and submit transactions to those streams.

Ceramic accounts exist in form of Decentralized Identifiers (DIDs). DIDs enable users to control and manage their Ceramic accounts (i.e. DID) from multiple Web3 wallet accounts across different blockchains - conferring on them ‘interoperability’.

The default DID for Ceramic is **3ID** (i.e. Three ID). 3IDs are mutable DID methods that support multi-accounts, and cross-chain identities which enables users to control their 3ID DID from their existing web3 wallets without any external software.

On the other hand, the default DID for ComposeDB is **PKH DID** (i.e. Public Key Hash DID). PKH DID is a DID method that natively supports blockchain accounts. It allows users to only sign in with their blockchain wallet once and further sign Ceramic transactions in their browser for the duration of the session.

### 5. **Indexing**

The present Ceramic infrastructure is void of data indexing. This gap is filled by ComposeDB.

ComposeDB enables indexing by each Ceramic Node.

### 6. **Authentication Mechanisms**

In the Ceramic ecosystem, authentication involves users writing, signing or decrypting data. Stream types specify their authentication process and dictate the validation mechanisms for adding new data to a particular stream.

ComposeDB currently supports DID as one of its authentication mechanisms. DIDs enable documents to contain public keys for signature verification and encryption.

As opposed to Ceramic which characterizes all or nothing permission model, ComposeDB supports highly detailed permission for each model.

### 7. **Data Model Reusability and Composability**

At the time this tutorial was written, developers building with Ceramic leverage Ceramic’s data model reusability and composability feature through <u>the GitHub Data Models Registry</u> - which is a tedious process, as they have to manually submit these data models.

This will change with ComposeDB.

Compose DB eases the workload by automatically indexing data models, making data reusability, retrieval, and discovery a walk in the park.

### 8. **User Experience**

One of the core components of the Ceramic data network is its “web3 sign-in” feature which allows users to sign in to apps/sites with ‘one-click’ - while also retaining ownership and control of their data in the same stead.

The current Ceramic framework is limited to specific Ceramic sign-in pop-ups, which needs to be broadened for Ceramic to achieve its full potential.

ComposeDB will utilize the "DID sessions" library to expand the scope of sign-in flows and data access patterns on Ceramic.

With the new integration, users can seamlessly sign in with their wallet, and delegate actions and storage permissions to developers. Developers have also been enabled the leeway to request specific data models and composites.

### 9. **Developer Experience**

Putting all these together, we can say certainly, that ComposeDB makes the developer experience streamlined, easier and more efficient.

ComposeDB lifts all the heavyweight of having to deal with multiple patchworks of client libraries (which we see with present-day Ceramic) and substitutes them with more galvanized workflow and optimized tooling.

Surely, this is a great development for developers.👍🏽

## **Finally…**

![Ceramic Illustration](https://github.com/midesofek/Ceramic-Tutorial-by-Mide-Sofek/blob/master/public/Final-Ceramic-Graphics.png?raw=true)

If you ever get confused about the difference between Ceramic and ComposeDB, just remember that Ceramic is a data protocol and ComposeDB is built on Ceramic.

ComposeDB doesn’t displace the Ceramic data protocol. Instead, it enhances and scales the features and operations of the present Ceramic network.

Thus creating an efficiently streamlined ecosystem for data, users and developers.
