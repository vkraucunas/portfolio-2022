<template>
  <main id="main">
    <h2>Hi There!</h2>
    <!-- <div class="flexRow">
      <img src="../../public/me2.gif" />
    </div> -->
    <p>
      I'm Valerie <a href="#name">Kraucunas</a>, a Senior UX Engineer
      specifically interested in a position on a design system team and other
      opportunities that participate in the complex intersection of Development
      and Design. My skill set positions me uniquely to help level up your team
      and gain momentum on the roadmap goals.
    </p>

    <h2>Why Design Systems?</h2>
    <p>
      The blend of efficient development effort, systems thinking, and design
      thinking is satisfying to me.
    </p>
    <p>
      Design system work is a puzzle that requires the usability consideration
      of multiple user groups: feature developers and designers, as well as
      end-users. For consuming developers and designers, this involves providing
      documentation to empower them with discoverable information, a path for
      feedback and contributions, and thoughtful systemization that becomes
      intuitive with time and use.
    </p>

    <p><strong>Design Token?</strong></p>
    <p>
      “Codification of design decisions for a consumable, versioned 'source of
      truth'.“
    </p>
    <p>
      In a design token library, you'll find a variable collection with all the
      heights, colors, animation timings, border radii, etc, for every system
      component for your platform. The compelling challenge of design token work
      is discerning the boundary of effective communication of Design's
      decisions while not dictating the component development approach.
    </p>

    <p>
      TL;DR Have you ever found 50+ grays in a codebase before? I have! There's
      a better way. <a href="#">Check out the tokens for this site</a>
    </p>

    <h2>Specialties and Experience</h2>

    <ul>
      <li>
        <h3>Design System Engineer</h3>
        <p>
          A year-plus spent on a cross-functional, enterprise design system
          team, where I independently established standards for and built out a
          multi-platform design token library and participated in a swarm effort
          to write components that consumed those tokens. Discovery and
          corrections from the implementation effort helped me increment the
          token library from alpha to beta; ultimately delivering a complete,
          documented set of tokens for web, most tokens for TV, and core tokens
          for Android SDK use.
        </p>
      </li>
      <li>
        <h3>Prototyper</h3>
        <p>
          Over two years embedded in a multidisciplinary design group building
          high-fidelity code prototypes for rapid proof of concept and user
          testing. Heavily focused into advanced settings screens in user
          portals, I acted as a "front-end dev in the room," able to engage the
          hypotheticals and answer questions early in the process. I enjoy
          design + dev pairing sessions to work through the details.
        </p>
      </li>
      <li>
        <h3>Accessibility Advocate</h3>
        <p>
          User-focused development is my work.
          <a
            href="https://www.cdc.gov/ncbddd/disabilityandhealth/infographic-disability-impacts-all.html"
            target="_blank"
            >One in four adults in the US live with a disability.</a
          >
          I have surfaced accessibility improvement opportunities to every job
          I've had as an engineer. I am currently working thru Deque
          University's Web Accessibility curriculum.
        </p>
      </li>
      <li>
        <h3>Mentor</h3>
        <p>
          After graduating code school, I participated in a residency program
          and taught a cohort of students making the career change like myself.
          While there I learned how to teach, strengthened my technical speaking
          and translating muscles, and became comfortable with live coding.
        </p>
        <p>
          More recently, I maintain multiple mentees. I enjoy using code review,
          professional coaching including resume review, and some emotional
          support to build their confidence as they join the industry and find
          their way. I have been a moderator of the Denver Devs online community
          since 2018, and take the role modeling and empathy aspects of
          leadership seriously.
        </p>
        <p>
          I am a firm believer that companies that won't hire and support junior
          engineers are doing active harm to the diversity and sustainability of
          the industry.
        </p>
      </li>
      <li>
        <h3>Organizational Coach</h3>
        <p>
          Does your team need an intake to release workflow that doesn't leave
          out anyone or drown them in details and meetings outside their area of
          concern? With a work history including administrative work and
          community management, I am a whiz at team process design.
        </p>
        <p>
          Finally, I have supported multiple design teams in adapting the agile
          workflow to suit their needs. Articulating the technical and cerebral
          aspects of design work into tickets
        </p>
      </li>
    </ul>

    <h2>What have I built?</h2>

    <ul>
      <li>
        User portals for VR field trip experiences, internet and phone services,
        social media, and inbound call centers
      </li>
      <li>Component libraries</li>
      <li>Design token library</li>
      <li>High fidelity prototypes</li>
      <li>White label applications</li>
    </ul>

    <h2>What do I work with?</h2>
    <p>JavaScript/Typescript, React, Vue, SCSS, Style Dictionary</p>
    <p>
      Other technology and tooling I am familiar with includes Node, Express,
      PostgreSQL, Git, Github, Gitlab, Jest, Mocha/Chai, ESLint, JIRA, Trello,
      Asana
    </p>

    <h2 id="name">How is Kraucunas pronounced?</h2>
    <p>
      <em><strong>“cruh soon uss”</strong></em>
    </p>
    <p>It trips up most folks. No biggie. ¯\_(ツ)_/¯</p>

    <h2>Anything else?</h2>
    <p>I'm a multipassionate maker. I do headshot photography,</p>
    <p>
      I live in Denver with my partner and our three adorable dogs. We are both
      software engineers, so I navigate platform and devops conversations daily.
      In my free time, I enjoy too many creative hobbies and gardening.
    </p>
  </main>
</template>

<script>
export default {
  name: "VKContent",
};
</script>

<style lang="scss">
@import "../assets/core.scss";

main {
  display: flex;
  flex-direction: column;
  text-align: left;
  width: 90%;
  min-height: 60vh;
  flex-grow: 1;
  background-color: rgba(44, 53, 32, 0.6);
  padding: 2.5rem;
  margin-bottom: 3rem;
  margin-right: auto;

  p {
    line-height: 1.8;
    padding-right: 18%;
  }

  @media screen and (min-width: 600px) {
    width: 80%;
    max-width: 1280px;
    padding: 4rem;
  }

  .flexRow {
    display: flex;
    align-items: center;
    justify-content: space-between;
    img {
      height: auto;
      max-height: 400px;
    }
  }
}
</style>
