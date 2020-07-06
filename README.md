# manifest-destiny

\section{Motivators}

What's wrong with the internet today?
What's wrong with the web today?

\section{On-boarding}

Social media today are comparable to giant walled gardens.
They mostly don't play well with each other and alternatives are isolated by being extremely difficult to carry personal data from one platform to the other.

\subsection{Solution}
The way we envisioned to "tear down those walls" (that does not depend on the social media providers' willful cooperation) uses 
-automated web-scraping tools to download all user-accessible data to users' machines.
-parsing scripts to structure the data in a self-verifiable (hashing), deterministic (content-addressing), convergent, and serializable fashion to ease data-sharing among users.
-a BitTorrent-like (probably IPFS) data-sharing protocol that enables users to download content from each other, as well as searching for it.
-a front-end to allow users to interact with the (now owned by everyone) data.

\subsection{Planned side-effects}
This plan is an attempt to empower users over their data and over the way they want to interact with it (e.g., using a front-end to access one's Instagram DMs or a different recommendation algorithm for one's TikTok For You page) and diminishing the walled-garden-granted "power" social media platforms might have over their users (e.g., hindering creators' reach because of their political opinions or making obscene changes to their apps' interfaces).
It'll allow for much easier historical archiving efforts as content will be seldom lost\footnote{due to there being control mechanisms (probably some sort of DHT) tracking what data each host/node has. Nowadays, there could even be many copies of a file out there, but no way for anyone to find it and download it.}
 
