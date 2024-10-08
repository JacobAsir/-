# 𝗔𝗜-𝗗𝗿𝗶𝘃𝗲𝗻 𝗔𝘁𝘁𝗿𝗶𝗯𝘂𝘁𝗲 𝗘𝘅𝘁𝗿𝗮𝗰𝘁𝗶𝗼𝗻

𝗧𝗵𝗲 𝗖𝗵𝗮𝗹𝗹𝗲𝗻𝗴𝗲 𝗮𝗻𝗱 𝗔𝗽𝗽𝗿𝗼𝗮𝗰𝗵
In marketplaces like Mercari, understanding the precise details in a listing description is crucial. These descriptions often contain important attributes such as size, color, and condition, which can significantly impact a listing's effectiveness. Inspired by Mercari's approach, I set out to create an AI model that could automate the extraction of these key details from product descriptions.

𝗠𝘆 𝗦𝗼𝗹𝘂𝘁𝗶𝗼𝗻
To tackle this challenge, I used the LangChain framework with the Cohere model, specifically the 𝗰𝗼𝗺𝗺𝗮𝗻𝗱-𝗿-𝗽𝗹𝘂𝘀-𝟬𝟴-𝟮𝟬𝟮𝟰.

𝗗𝗲𝗳𝗶𝗻𝗶𝗻𝗴 𝘁𝗵𝗲 𝗧𝗮𝘀𝗸: I set up a system prompt for the AI assistant to extract key attributes from product descriptions. The goal was to identify details like size, color, original retail price, and condition.

𝗘𝘅𝗮𝗺𝗽𝗹𝗲𝘀 𝗮𝗻𝗱 𝗧𝗲𝗺𝗽𝗹𝗮𝘁𝗲𝘀: I created a series of examples with human-provided inputs and expected AI outputs to guide the model. These examples included various product descriptions, demonstrating how to extract relevant information.

𝐈𝐦𝐩𝐥𝐞𝐦𝐞𝐧𝐭𝐢𝐧𝐠 𝐰𝐢𝐭𝐡 𝐒𝐭𝐫𝐞𝐚𝐦𝐥𝐢𝐭: I built a simple user interface using Streamlit. This allows users to input a product description and receive attribute extraction results in real-time

𝗜𝘁𝗲𝗿𝗮𝘁𝗶𝘃𝗲 𝗣𝗿𝗼𝗰𝗲𝘀𝘀:The model uses a template-based approach where input descriptions are processed, and attributes are extracted using predefined templates and the Cohere model. 
