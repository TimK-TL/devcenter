---
title: Scheduling your builds
redirect_from:
- "/builds/scheduling-builds/"
- "/builds/scheduling-builds"
tag:
- builds
- triggers
summary: You can schedule your builds to run automatically at a specific time of the
  week so that you can check your logs when it's most convenient for you.
menu:
  builds-main:
    weight: 10

---
You can schedule your builds to run automatically at a specific time of the week so that you can check your logs when it's most convenient for you.

Follow the steps to see how you can set it up for your next build!

1. Go to your [Dashboard](https://app.bitrise.io/dashboard) and click on the project whose build you want to schedule.
2. Click on **Start/Schedule a Build**.
3. In the **Build configuration** pop-up window, toggle the switch to the right to enable `Schedule this build` feature.

   ![](/img/basic-build-config-1.jpg)
4. Set the hour and minute in the `HH/MM` field.
5. On the timeline, select the day(s) when you want your build to run.

   ![](/img/basic-build-config-scheduled-1.jpg)
6. Check and fill out the rest of the input fields if necessary. You can schedule your build in the advanced version of the `Build configuration` window too.
7. Click `Schedule Build` at the bottom of the pop-up window.

{% include message_box.html type="info" title="Conflicting input" content="Using the Advanced option, you have access to additional options for your build: you can enter a git tag or a commit hash. If, for example, you specify a commit hash, you will notice that the Git Tag option disappears. This ensures that you cannot enter conflicting input values.

If you specify a commit hash and a branch where that commit does not exist (for example, **master**), Bitrise will find the branch that does have the given commit (for example, **testing**) and run a build with that branch. "%}

Now you're back on your **Builds** board and you can see your scheduled build.

If you click on **Show scheduled**, you can edit/delete your schedules, disable build scheduling by toggling the switch to the left, or immediately trigger the build by clicking on the **Trigger now** button.

![Screenshot](/img/scheduling-builds/scheduled-build.png)

That's it! Now you can enjoy the comfort of your automated build!

<div class="banner">
<img src="/assets/images/banner-bg-888x170.png" style="border: none;">
<div class="deploy-text">Let's schedule a build!</div>
<a target="_blank" href="https://app.bitrise.io/dashboard/builds"><button class="button">Go to your app</button></a>
</div>