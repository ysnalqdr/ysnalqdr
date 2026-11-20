# Muhammad Yasin Al'Qadri

Information Technology student at Bina Sarana Informatika University, focused on backend engineering.
Looking for a backend internship in 2027.

I build small services and write down what I learn. Right now my main focus is Java
and Spring Boot; the project below was built with Node.js, which is what I had before
I started on Java.

Most of what I know came from building and breaking things. When something does not
work, I read the error, check the docs, and write down what went wrong so I do not
repeat it.

## Skills

| Level | Technologies |
| :--- | :--- |
| **Core** | Java, JavaScript, Node.js, Express, MySQL, Git |
| **Working knowledge** | PHP, Laravel, PostgreSQL, Firestore |
| **Currently learning** | Spring Boot, Go, TypeScript, Python, Docker, Linux |

Grouped by depth of use, not by how many I can name. Anything outside Core still
needs the documentation open while I work.

## Featured project

### SoundWave concert ticketing
A ticketing system for concerts. Users pick a seat, pay through a payment gateway,
and get a QR ticket that can be checked offline.

- Backend in Node.js and Express, data in Firestore
- Payments through Midtrans, with webhook signatures verified server-side
- Each ticket is signed with Ed25519, so it cannot be forged
- Client app in Flutter
- Test suite covering pricing, stock, refund, and notification flows

The part that took the longest was seat booking. Two people can click the same seat
at almost the same moment, and only one of them should get it. I used an atomic
transaction so the second request fails cleanly instead of double-booking.

[backend](https://github.com/ysnalqdr/soundwave-backend) · [client](https://github.com/ysnalqdr/SoundWave)

## Education

**Universitas Bina Sarana Informatika**  S1 Teknologi Informasi, 2024 – present

Relevant coursework: Database Systems, Data Structures and Algorithms, Computer
Networks, Operating Systems, Web Programming.

## Currently

Following a 48-week plan: Java fundamentals → Spring Boot → deployment. Weekly notes
and mistakes go in [backend-journey](https://github.com/ysnalqdr/backend-journey).
