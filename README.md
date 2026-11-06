<div align="center">

# Muhammad Yasin Al'Qadri

Information Technology student, learning backend engineering.

I build small services and write down what I learn. Currently working toward a
backend internship in October 2027.

<img src="https://skillicons.dev/icons?i=java,spring,go,js,nodejs,express,laravel,mysql,postgres,docker,git,linux&theme=dark" alt="Java, Spring, Go, JavaScript, Node.js, Express, Laravel, MySQL, PostgreSQL, Docker, Git, Linux" />

<br />

<a href="https://github.com/ysnalqdr/backend-journey"><img src="https://img.shields.io/badge/48--week_roadmap-in_progress-2ea44f?style=flat-square" alt="Roadmap"></a>

</div>

---

## About

I'm a Information Technology student from Indonesia. I like the backend side of things —
APIs, databases, authentication, and payments.

Right now my main focus is **Java and Spring Boot**. I also use **Node.js** and
**Laravel**, and those are what I've built my projects with so far. I'm still early
in this, so I try to keep the work small and finish it properly rather than start
many things at once.

Most of what I know came from building and breaking things. When something doesn't
work, I read the error, check the docs, and write down what went wrong so I don't
repeat it.

## Projects

### SoundWave — concert ticketing
A ticketing app for concerts. Users pick a seat, pay through a payment gateway, and
get a QR ticket that can be checked offline.

- Backend in Node.js and Express, data in Firestore
- Payments through Midtrans, with webhook signatures verified server-side
- Each ticket is signed with Ed25519, so it can't be faked
- Client app in Flutter

The part that took the longest was seat booking. Two people can click the same seat
at almost the same moment, and only one of them should get it. I used an atomic
transaction so the second request fails cleanly instead of double-booking.

[backend](https://github.com/ysnalqdr/soundwave-backend) · [client](https://github.com/ysnalqdr/SoundWave)

### SiDamkar — fire reporting
A web app for reporting fires and coordinating a response. It has a panic button for
emergencies, guest access for people who don't have an account, and separate
dashboards for citizens, officers, and admins.

- Laravel 10, MySQL, Blade

[repository](https://github.com/ysnalqdr/SiDamkar)

### E-commerce platform
An online store with three roles: buyer, seller, and admin. Sellers manage products,
buyers check out with a cart, and payments go through Midtrans.

- Laravel 12, MySQL, Tailwind CSS

[repository](https://github.com/ysnalqdr/ecommerce-app)

## Currently

- Following a 48-week plan: Java fundamentals → Spring Boot → deployment
- Writing weekly notes and mistakes in [backend-journey](https://github.com/ysnalqdr/backend-journey)
- Target: backend internship, October 2027

---

<div align="center">
  <sub>Open to internship opportunities</sub>
</div>
