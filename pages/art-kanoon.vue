<template>
  <div>
    <NavBar />
    <div class="content content-post">
      <div class="header">
        <img src="/artkanoon_cover.png" alt="Art Kanoon" />
      </div>
      <h1>Art Kanoon</h1>
      <div>
        <h2>Project Overview</h2>
        <p>
          Originally started as a comic magazine, Art Kanoon publishing house
          wanted to transition to a digital platform presenting web-comics to a
          more versatile and global audience.
        </p>
        <p>
          We started by developing a beta version of the platform and
          maintaining it for 8 months collecting user feedback, then moved on to
          designing and implementing the new features.
        </p>
        <h2>Key Challenges and Constrains</h2>
        <ul>
          <li>
            Designing multiple layouts for the platform (Arabic and English,
            Dark mode and Light mode) and ensuring they all fit the brand and
            tone of Art Kanoon
          </li>
          <li>
            Developing a comics reader that allows for various ways of
            navigating around the comic and switching between languages smoothly
          </li>
        </ul>
        <h2>Design Process</h2>
        <img src="/sudanmoves/design_process.png" alt="Design Process" />
        <p>
          After the initial meeting and product definition, we set out to do the
          research. There are a lot of other online web-comic platforms, but
          none of them truly caters to Arabic-speaking audience, so we took what
          we thought these platform did right and added our own features and
          tweaks.
        </p>
        <h3>Prototyping</h3>
        <p>
          After all research is done and info is collected, we conducted
          analysis and shared the results with the team in the shape of
          prototypes.
        </p>
        <img src="/sudanmoves/prototyping.png" alt="Prototyping" />
        <h3>Design & Testing</h3>
        <p>
          After the results of the beta test we set out to collect and analyse
          feedback.
        </p>
        <p>The results of the analysis was as follows:</p>
        <ul>
          <li>80% of users browse on mobile/tablet</li>
          <li>
            Most of the users preferred light mode by default and only few opted
            to use dark mode
          </li>
          <li>
            Around 60% used the website’s english version but some of them
            switched to arabic to read the comics
          </li>
        </ul>
        <p>
          After completing the analysis, it was time to work on the final
          version of the platform.
        </p>
        <p>The steps we took out based on the analysis:</p>
        <ul>
          <li>Implement a mobile-first design approach</li>
          <li>
            We added a code that detects the user’s OS color mode and decide
            whether to serve the light or dark version of the platform (
            defaults to light-mode )
          </li>
          <li>
            We used the same code again to decide the default language of the
            platform, and we added an option to switch the chapter’s language
            without changing the whole platform’s language
          </li>
        </ul>
        <h2>Final Results</h2>
        <img src="/artkanoon/artkanoon-1.png" alt="Final Results 1" />
        <img src="/artkanoon/artkanoon-2.png" alt="Final Results 2" />
        <img src="/artkanoon/artkanoon-3.png" alt="Final Results 3" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
html {
  scroll-behavior: unset !important;
  color: red;
}
</style>
