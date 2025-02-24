# v0 by vLayer

A robust, multi-layered solution that leverages vlayer’s innovative features to securely issue proof-of-attendance NFTs for live events. This platform not only confirms on-site participation through geo-fencing and AR image capture but also integrates social media verification, historical on-chain state validation, and rewards activation—ensuring a comprehensive and engaging user experience.


![image](https://github.com/user-attachments/assets/20ac4c55-82d5-42a5-8f70-93c1e4be1760)


---

## Project Overview

This project is designed to provide event organizers with a secure and interactive method to distribute proof-of-attendance NFTs. Attendees can verify their presence at an event via multiple steps including email verification, geo-fencing, AR image capture, and social media engagement. In addition, the platform utilizes vlayer’s advanced features—such as time travel for historical on-chain state verification and email verification—to offer retroactive rewards and a dynamic loyalty program.

---

## Key Features

- **Email Verification with vlayer**  
  - Securely verify participant emails using vlayer’s email verification feature.  
  - Ensure authenticity by allowing only invited users (e.g., via [lu.ma](http://lu.ma)) to register.  
  - [Learn more about vlayer Email Verification](https://book.vlayer.xyz/features/email.html).

- **Event Check-In (Geo-Fencing)**  
  - Confirm physical presence at the event with real-time geo-fencing.  
  - Seamlessly integrate location-based validation to ensure on-site participation.

- **AR Image Capture**  
  - Enable attendees to capture an augmented reality (AR) image once their location is verified.  
  - Automatically attach the captured AR image to the NFT metadata.

- **Social Media Engagement**  
  - Guide users to post on X (formerly Twitter) with a sample text, event hashtag, and sponsor tags.  
  - Verify posts using zkTLS and web proofs to ensure authenticity and engagement.  
  - Embed the verified post URL into the NFT metadata.

- **Historical State Verification (Time Travel)**  
  - Utilize vlayer’s time travel feature to verify historical on-chain states, such as pre-event asset holdings.  
  - Allow for retroactive rewards or loyalty benefits based on validated historical data.

- **NFT Issuance & Rewards Activation**  
  - Automatically mint proof-of-attendance NFTs once all verifications are complete.  
  - Unlock access to future rewards and loyalty programs via NFT ownership.

- **User Dashboard**  
  - Provide a dedicated dashboard where users can view their minted NFTs, event history, and claim additional rewards.  
  - Offer insights and further details on the loyalty program.

---

## User Flow

1. **Landing Page**  
   - Introduces the event, highlights benefits, and displays clear call-to-action buttons.

2. **Registration & Email Verification**  
   - Users register by entering their email address.  
   - vlayer’s email verification is triggered to ensure secure registration.

3. **Event Check-In (Geo-Fencing)**  
   - Upon arrival, the user is prompted for location access.  
   - The system validates the user’s presence within the geo-fenced event area.

4. **AR Image Capture**  
   - Once the location is verified, the user captures an AR image using a built-in interface.  
   - The image is attached to the NFT metadata.

5. **Social Media Engagement**  
   - Users are instructed to post on X with event-specific content (including the captured AR image).  
   - The post is verified via zkTLS and web proofs, and its URL is embedded in the NFT.

6. **Historical State Verification (Time Travel)**  
   - vlayer’s time travel feature confirms the user’s historical on-chain states, ensuring eligibility for rewards.

7. **NFT Issuance & Rewards Activation**  
   - After all validations, a smart contract mints the proof-of-attendance NFT and activates any associated rewards.

8. **User Dashboard**  
   - The dashboard displays minted NFTs, event history, and additional rewards or loyalty benefits.

---

## Technologies Used

- **vlayer**  
  - Utilized for email verification, time travel (historical on-chain state verification), and more.
- **Geo-Fencing APIs**  
  - For real-time location tracking and on-site attendance validation.
- **AR Image Capture Tools**  
  - Enable the integration of augmented reality features within the application.
- **zkTLS & Web Proofs**  
  - Ensure secure and verifiable social media post validation.
- **Smart Contracts**  
  - Handle NFT minting and rewards activation on the blockchain.
- **Modern Frontend Frameworks**  
  - Build an intuitive, responsive, and user-friendly interface.

---

