<script lang="ts">
    const slackLogo = "../logos/slack-logo.svg";
    const gmailLogo = "../logos/gmail-logo.svg";

    let isGmail = false;
    const logo: string = (isGmail) => {
        if (isGmail) {
            return gmailLogo;
        }
        else {
            isGmail = true;
            return slackLogo;
        }
    }
</script>

<div>
    <img src={logo} alt="">
    <div>
        <div></div>
        <div></div>
        <div></div>
    </div>
</div>
