1. GUI and Front-end:
- Web Client Model: Utilizes a combination of custom implementations found in the source code, including JavaScript for rendering and interactive elements.
- 2.5D GUI: Create a cohesive blend of 2D and 2.5D interfaces, allowing users to switch between traditional chat views and 2.5D visualizations, depending on preference and need.
- Interactable 2.5D Objects: Through developer-created plugins, users can interact with 2.5D objects within the "subchats," such as playing videos on 2.5D-rendered pop-up screens.
- Adaptive Layout: The 2.5D display adapts to various devices and screen sizes, maintaining the depth effect across platforms.
- Subchat: Chat rooms that you can make in your own "homespace."
- Homespace: Splinterstice's very own equivalent of both a Discord "server"/Matrix space and a Matrix/XMPP homeserver, rolled into one.
- Collapsible User and Homespace/Subchat Lists: A blend of simple navigation and modern design to create collapsible lists for homespaces, subchats, DM group chats, and DMs (for optimizing space usage).
- Drag-and-Drop File Sharing: Integrating file-sharing capabilities with a drag-and-drop interface that supports various file types, allowing users to easily share and preview files within both subchats, DMs, and DM group chats.
- Friend Request Option: Have the ability to send friend requests.
- DM Group Chats: Have the ability to make DM group chats with a maximum of 10 people.
- Message Forwarding: Similar to the "forward messaging" seen on messaging platforms such as Discord as well as some of Matrix's clients.
- User-Friendly Interface: A simple, intuitive interface allows users to easily explore and apply 2.5D customization options, even if they have no technical background.
- 2.5D Tabbed Interface Feature: Introduces a user interface within Splinterstice that organizes various homespaces, subchats, DM group chats, or other digital elements in a tabbed format (with a depth effect). Tabs can be rearranged via simple drag-and-drop, accompanied by a smooth 2.5D transitional animation.
- Responsive Tab Management: Depending on the screen size, tabs can be expanded, condensed, or stacked, always maintaining the 2.5D depth effect.
- Quick Access Toolbar: A dedicated toolbar in the 2.5D environment provides instant access to essential features or settings related to the tabbed interface.
- Integration with 2.5D Video Display: Tabs can contain multimedia content previews, including the aforementioned 2.5D video display feature, offering a consistent visual experience.
- 2.5D Tabs: Each tab represents a distinct homespace, channel, or conversation and has a subtle depth effect, providing a more tactile and visually engaging experience.
- Interactive Hover Effects: Hovering over a tab will show a slight 3D shift or preview of the content, adding to the dynamic 2.5D visual experience.

2. Features for Secure Accessibility and Encryption:
- Random URL Generation Functionality: A random URL regeneration occurs every time the user switches to another tab, ensuring the URL cannot be copied and pasted or linked to others. The page automatically refreshes to regenerate a different string of numbers for the URL.
- Access Through Name Only: The platform can only be found if the name is known, publicized exclusively on Tor and I2P.
- Individualized Key-Codes: Upon registration on the .onion or eepsite page, users receive individually assigned key-codes for accounts. These key-codes allow access to the project from anywhere online, functioning similarly to a crypto wallet.
- Secure Digital Handshake (SDH): Custom-made digital handshaking protocol to securely confirm identity or agreements within the platform during the account registration process, before individually assigning the user their own individual "key-code". This should be able to be done via both encrypted signature for identity verification, followed by an animated 2.5D handshake that represents the completion of the verification process.
- Dedicated e2ee Subsystem: A dedicated e2ee subsystem will be developed server-side to execute the concept of individualized "key-codes" and to hide server-side exit nodes and user IP addresses across both darknet services.
- Secure 2.5D GUI Alignment: Align the 2.5D visualization features with the strong privacy and security principles of Splinterstice, ensuring that the 2.5D environment does not compromise user data or communication integrity.
- Network Independence: Hosted on the head developer's personal device, not solely relying on Tor or I2P network nodes.
- Secure Homespaces: Controls in "homespace" settings for ensuring that homespaces can be private or public, with cryptographic verification.
- Media Security Controls: Ensures that media of all sorts can be shared privately or publicly within a homespace, with options for cryptographic access.

3. Guild Topology:
- Inter-Socket Communication: Highly coordinated communication protocols would be crucial, which might involve RESTful APIs, WebSocket connections, and or other TCP/UDP based communication protocols.
- Self-Sufficiency: Each socket endpoint should be designed to operate independently, ensuring the network's functionality even if some endpoints are down.
- Adaptability: The system needs to be capable of dynamically adjusting to changes, such as varying data loads or the addition/removal of socket endpoints.
- Self-Healing: The network should automatically reroute connections and redistribute loads in case of endpoint failures. Techniques like circuit breakers in microservices could be analogous.
- Scalability: The addition of new socket endpoints should be seamless, possibly facilitated by containerization and orchestration tools like Docker and Kubernetes.
- Auto-enabled Sockets: Every time someone makes a "homespace" on Splinterstice, a dedicated set cluster of a few network sockets is automatically generated and enabled for that specific "homespace". Meaning that if anything ever happens to the main device that Splinterstice itself is hosted on, to make it where it's not up or whatever else, then at least the "homespaces" won't be affected by it. This is to be in accordance, to the aforementioned features of the Guild Network Topology, that have been listed above.

4. Mass Customization and Self-Hosting:
- No Third-Party Dependency Nor Monetization: Enables mass customization of standard web-client's front-end.
- Self-Hosting Option: There should be an option in the settings of any user's own "homespace", to host their "homespace" that they've made via clicking the "+" icon for creating your own "homespace" within its settings, on their own virtualized/emulated server and or physical device. This is similar to the idea of self-hosting for a Matrix or XXMP home server.
- Dynamic 2.5D Environment Customization: A feature that allows users to personalize their front-end for the standard web-client, through an in-built customization toolkit. It combines the extensible nature of the existing architecture with user-friendly customization, creating a pseudo-3D effect for their UI.
- Customizable UIs: Leveraging flexibility in UI customization, users can personalize their chat environment, including the design of the 2.5D-rendered pop-up screens and other visual elements.
- Theming and Personalization Options: Offering users extensive control over the appearance, including colors, fonts, layouts, etc. An example being the option for "homespace" owners to set different digital settings (like a virtual café, library, or outdoor park).
- Integration with Homespace Themes: The 2.5D video display can align with the overall theme or design of the "homespace", offering a seamless and cohesive visual experience.
- Avatar Customization: Users can also create and customize their avatars, selecting from a range of pre-designed models or using third-party plugins to craft something truly unique.
- Customizable Tab Design: Users can personalize the appearance of tabs, adjusting colors, icons, or effects to align with their preferences or homespace themes.
- Real-Time Translation Option: An option leveraging a real-time translation feature, allowing for instant translation of messages for international collaboration. Paired with an extensive language list for choosing which language to translate it to.

5. Ethical Guidelines and Compliance:
- Freedom of Speech/Expression Policy: You can technically say and post whatever you want to, so long as it doesn't explicitly violate Splinterstice's ToS, cause keep in mind that Splinterstice is still a freedom of speech/expression absolutist platform, in the end of the day.
- ToS: By registering for your own Splinterstice account, you thereby agree to services being demonstrably cut off if you (for whatever reason(s)) decide to cross the line into partaking in explicitly illegal acts on the messaging platform. This includes activities such as the distribution/consumption of CSAM, using it as a storefront to sell to/scam others, running criminal operations, actively planning physical attacks against certain individuals/groups, and doxing others.
- automod bot: This bot only reacts to users who's explicitly volated the ToS, as if they do so, then the bot shall automatically cut off services for them and automatically generate a report of their specific violation for Splinterstice's host.