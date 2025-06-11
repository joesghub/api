# What the Heliantte is a REST API?

🧠 Have you ever wondered how LinkedIn keeps your profile, posts, and activity up-to-date—or how it instantly loads more content as you scroll?

That seamless experience is largely powered by something we’re learning in the first weeks of the ***RiseUp with ServiceNow Innovation Hub in partnership with Kura Labs***: RESTful APIs.

📖 **API** stands for Application Programming Interface—a set of rules that allows different software systems to talk to each other.

😋 Think of it like a restaurant: you (the client) place an order with the waiter (API), who takes it to the kitchen (server) and returns with your food (data). Similarly, when your device makes a request, the server sends back what was asked for

![Api as a Restaurant Order](https://github.com/joesghub/api/blob/main/images/apis%20as%20a%20restaurant-Page-2.drawio.png?raw=true)

🤝🏾 Once rules are established and systems are connected via the web, you have a working API.

 To improve performance and reliability, many APIs today follow REST principles—Representational State Transfer—which help make services more scalable, flexible, and independent.
 
😴 RESTful APIs are the most commonly used APIs across the internet. Let’s take LinkedIn, for example.

Every time you scroll, click, or update your profile, API calls are being made in the background. Each action—like loading your feed or sending a post—has a specific endpoint (a unique web address that handles that action).

👀 RESTful APIs help LinkedIn serve over 100 million users a day efficiently by ensuring those background interactions are fast, consistent, and reliable.

📈 Whether you realize it or not, APIs are everywhere. 

They power the responsiveness of your favorite apps, enable automation behind the scenes, and help platforms deliver a smooth user experience. 

In DevOps, understanding APIs is essential for integrating tools, automating workflows, and building scalable services.

## 🔄 An API Request in a Client-Server Model – Step-by-Step Summary

**🧠 Key Concept**

This diagram illustrates how an API request flows between a client and a server using a real-world example from the PokéAPI.
This is a classic RESTful API interaction—the client makes a request to an endpoint, and the server returns the data in a structured format, enabling the app to update content in real time.

![Api request in a Client Server Model](https://github.com/joesghub/api/blob/main/images/apis%20as%20a%20restaurant.drawio.png)

**Step 1: Client Sends API Request**
- A client (like a web or mobile app) initiates a GET request to the API using a specific endpoint.

- In the example shown, the client is requesting data about the Pokémon "Ditto" using the URL:
https://pokeapi.co/api/v2/pokemon/ditto

**Step 2: Server Processes the Request**
- The server receives the request and determines what data is being asked for.

- It locates the appropriate information from its internal database or service.

**Step 3: Server Prepares the Response**
- The server formats the retrieved data (often in JSON) so the client can understand and use it.

- This data might include various fields like abilities, forms, experience, etc.

**Step 4: Client Receives the API Response**
- The client receives the response from the server, which now contains all the structured data for "Ditto".

In the image, the returned JSON includes:
- A list of abilities with links to additional data

- Base experience and cries

- A form name and its own API link


