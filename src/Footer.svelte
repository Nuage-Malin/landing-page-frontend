<script>
</script>

<footer>
    <div class="container flex">
        <div class="center-items" style="padding-block: 1rem;">
            <img
                class="logo"
                src="img/2024_logo_nuagemalin.png"
                alt="logo_NuageMalin"
            />
            <h1>Contactez-nous !</h1>
        </div>
        <div class="reseaux">
            <a href="https://www.instagram.com/nuagemalin/">
                <img
                    class="icon"
                    src="icon/instagram.png"
                    alt="contact_instagram_NuageMalin"
                />
            </a>
            <a href="https://www.linkedin.com/company/nuage-malin">
                <img
                    class="icon"
                    src="icon/linkedinBlue.png"
                    alt="contact_linkedin_NuageMalin"
                />
            </a>
            <a href="https://twitter.com/NuageMalin_fr">
                <img
                    class="icon"
                    src="icon/twitter.png"
                    alt="contact_twitter_NuageMalin"
                />
            </a>
        </div>
        <div class="center-items">
            <h3>nuagemalinfr@protonmail.com</h3>
        </div>
    </div>
</footer>

<style>
    footer {
        position: absolute;
        width: 100%;
        z-index: 9000;
        margin-top: -10%;
        background-color: white;
    }
    .flex {
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
    }
    .container {
        max-width: 50rem;
        margin-inline: auto;
        padding-inline: 3rem;
    }
    .center-items {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
    }
    .reseaux {
        display: flex;
        gap: 3rem;
        justify-content: center;
    }
    h1 {
        margin-block: 0;
        margin-inline: 0;
        color: var(--c-blue);
        font-weight: normal;
        font-family: var(--ff-t);
        font-size: var(--fs-xl);
    }
    h3 {
        margin-block: 1em;
        color: var(--c-blue);
        font-weight: normal;
        font-family: var(--ff-t);
        font-size: var(--fs-l);
    }
    .logo {
        width: 15rem;
    }
    .icon {
        width: 3rem;
    }
    @media (max-width: 71em) {
        footer {
            margin-top: -25%;
        }
        .icon {
            width: 2rem;
        }
    }
    @media (max-width: 25em) {
        footer {
            margin-top: -50%;
        }
        .logo {
            width: 10rem;
            object-fit: cover;
            height: 7rem;
        }
        .center-items {
            flex-direction: column;
        }
    }
</style>
