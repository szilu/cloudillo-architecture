Frequently Asked Questions
==========================

<details>
  <summary>What is Cloudillo, and what sets it apart from other collaboration platforms?</summary>
  Cloudillo is an open-source Operating System designed for collaboration. It
  provides standardized interfaces for developers to create applications
  involving creation, sharing, and collaboration.
</details>

<details>
  <summary>Can I use Cloudillo for personal projects, or is it primarily designed for businesses?</summary>
  Absolutely! Our primary focus is on personal use, such as social networking,
  content creation, and collaboration. It's also suitable for businesses, and
  we're planning features and services tailored for them. You can even develop
  your own applications and potentially earn money with them.
</details>

<details>
  <summary>What types of applications can be built on the Cloudillo platform?</summary>
  Cloudillo is ideal for content creation, sharing, and collaboration
  applications. This includes for example document editors, social network
  applications, and knowledge management tools. However, the platform is
  versatile, allowing the development of various applications, including games
  that can benefit from its globally accessible identity management.
</details>

<details>
  <summary>How does Cloudillo handle user authentication and authorization globally?</summary>
  Cloudillo utilizes an Identity System based on a Domain Name System (DNS),
  separating identity management from the hosting provider. This enables easy
  migration between providers or self-hosting.

  At first glance this might seem like an overkill and extra administration
  step to do, maybe involving extra costs, but not necessarily. If you already
  have a domain name than you can create unlimited identities for your
  coworkers, friends or family. For example I use szilard.hajba.eu as my
  personal identity and szilard.symbion.hu as my business identity.

  If you don't have a domain name than you will be able to create identities
  with an Identity Provider (for example cloudillo.org, or something similar).
  This, of course, has some drawbacks regarding vendor lock-in, but no more
  than the traditional cloud-based platforms.

  Once your identity is up, Cloudillo will create and publish a Signing Key
  what is used to sign all your action tokens in the Cloudillo inter-node
  communication.
</details>

<details>
  <summary>Is it possible to migrate data easily between different instances of Cloudillo or to self-hosting?</summary>
  Absolutely! Data backup and synchronization are core features. After
  migrating data to another node, you can update your record at the Identity
  Provider or DNS, facilitating a smooth transition to the new instance.
</details>

<details>
  <summary>What are the system requirements for self-hosting Cloudillo?</summary>
  Cloudillo is an Overlay Operating System, which means it runs on top of an other host OS.
  Our primary deployment method is a docker container, making it compatible
  with various operating systems, including modern NAS devices.
</details>

<details>
  <summary>How can I contribute to the development of Cloudillo, and what skills are needed to get involved?</summary>
  In the early development stages, we welcome contributors experienced in
  building the platform's base architecture. As the base APIs stabilize,
  there's an opportunity for Application Developers to contribute.

  Regardless of your expertise, your contribution is valuable as we build a
  thriving ecosystem of applications.
</details>
