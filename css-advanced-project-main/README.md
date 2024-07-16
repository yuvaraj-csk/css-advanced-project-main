# CSS ADVANCED PROJECT

### AIM:
    To create the Dribble website using HTML and CSS

### HTML CODE:
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <title>
          Dribbble - Discover the World’s Top Designers &amp; Creative Professionals
        </title>
        <meta
          name="description"
          content="Find Top Designers &amp; Creative Professionals on Dribbble. We are where designers gain inspiration, feedback, community, and jobs. Your best resource to discover and connect with designers worldwide." />
        <meta charset="utf-8" />
        <meta name="theme-color" content="#FFFFFF" />
        <meta
          name="viewport"
          content="width=device-width, initial-scale=1.0, minimum-scale=1.0" />
        <meta
          name="facebook-domain-verification"
          content="14yui0t6bj9n8uz4d48a2snpt3cvnz" />
        <meta property="fb:app_id" content="811749452338490" />

    <link
      href="https://cdn.dribbble.com/assets/dribbble-vector-ball-c75e531ccee3110d0ee5ae951fd1d0a65d2ff25d3c0577757ea7e8d8e3e75db4.svg"
      rel="mask-icon"
      color="#EA64D9" />
    <link
      href="https://cdn.dribbble.com/assets/apple-touch-icon-precomposed-182fb6df572b99fd9f7c870e5bd4441188121518640c0fa57782b258434d1e0f.png"
      rel="apple-touch-icon-precomposed" />
    <link
      href="https://cdn.dribbble.com/assets/favicon-452601365a822699d1d5db718ddf7499d036e8c2f7da69e85160a4d2f83534bd.ico"
      rel="icon"
      sizes="any" />
    <link
      href="https://cdn.dribbble.com/assets/favicon-192x192-d70ad402693bdd1a8460da7f9f3c590e817da7369c5287789ac968cf6947d214.png"
      rel="icon"
      sizes="192x192"
      type="image/png" />
    <link
      href="https://cdn.dribbble.com/assets/favicon-99944ff731bb44d3a947810ca8728f177f8deac035a3a4342120c385fd7acb9d.svg"
      rel="icon"
      type="image/svg+xml" />

    <meta name="csrf-param" content="authenticity_token" />
    <meta
      name="csrf-token"
      content="3TzvqxUVv4t0nsQt9619BjPm4bdJFCCLuERDeHNyZvgkzhQWewAQnOlKVqGh3eDXxLHZpdn4iTT86dLWZDEsoQ" />

    <meta name="referrer" content="origin-when-cross-origin" />

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Source+Serif+4:wght@400;600&family=IBM+Plex+Mono:wght@500&display=block"
      rel="stylesheet" />

    <meta name="mixpanel-controller" content="welcome" />
    <meta name="mixpanel-action" content="index" />

    <link
      rel="stylesheet"
      media="screen"
      href="https://cdn.dribbble.com/assets/welcome/index-35cc66cd64a897578dc8ae3365ed77079462abc2b577cadf4a460ea21ed4cfec.css" />
    <link
      rel="stylesheet"
      href="https://cdn.dribbble.com/assets/welcome/async-0524338e7cf71c7792b3f56a1ff90a40dbd05d7b9a4b9fa8800ae5d4a93d35a4.css"
      media="print"
      onload="this.media='all'" />
    <link
      rel="stylesheet"
      href="https://cdn.dribbble.com/assets/mini-master-async-85b313e3bc6b54f2be20a5a2e686357dbdde6231afa3089c7804685263851a47.css"
      media="print"
      onload="this.media='all'" />
    </head>

    <body
      id="page"
      class="logged-out not-pro not-player not-self not-team not-on-team no-hiring nav-v2-theme-cream">
      <div class="nav-v2" data-site-nav-v2>
        <div class="nav-v2__dark-overlay"></div>

      <div class="nav-v2__wrapper">
        <button
          class="nav-v2-burger"
          data-nav-v2-burger
          aria-label="Toggle mobile menu">
          <span></span>
          <span></span>
          <span></span>
        </button>

        <nav class="nav-v2-main" role="navigation" data-nav-v2-mobile>
          <div class="nav-v2-main__wrapper">
            <ul ul class="nav-v2-main__list">
              <li class="nav-v2-main__item nav-v2-main__item--sub-nav">
                <a data-nav-event-clicked="Hire Designers" href="/hiring"
                  >Find designers</a
                >

                <ul class="nav-v2-sub">
                  <li class="nav-v2-sub__item">
                    <a
                      class="nav-v2-sub__link"
                      data-nav-event-clicked="Designer Search"
                      href="/designers">
                      Designer search
                      <span class="nav-v2-sub__subtitle"
                        >Quickly find your next designer</span
                      >
                    </a>
                  </li>
                  <li class="nav-v2-sub__item">
                    <a
                      class="nav-v2-sub__link"
                      data-nav-event-clicked="Post a Job"
                      href="/hiring">
                      Post a job
                      <span class="nav-v2-sub__subtitle"
                        >The #1 job board for design talent</span
                      >
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-v2-main__item">
                <a data-nav-event-clicked="Inspiration" href="/shots/popular"
                  >Inspiration</a
                >
              </li>

              <li class="nav-v2-main__item nav-v2-main__item--sub-nav">
                <a data-nav-event-clicked="Learn Design" href="/product-design"
                  >Courses</a
                >

                <ul class="nav-v2-sub">
                  <li class="nav-v2-sub__item">
                    <a
                      class="nav-v2-sub__link"
                      data-nav-event-clicked="UX Diploma"
                      href="/ux-diploma">
                      UX Diploma
                      <span class="nav-v2-sub__subtitle"
                        >Learn UX design from scratch in 6 months</span
                      >
                    </a>
                  </li>
                  <li class="nav-v2-sub__item">
                    <a
                      class="nav-v2-sub__link"
                      data-nav-event-clicked="UI Certificate"
                      href="/ui-certificate">
                      UI Certificate
                      <span class="nav-v2-sub__subtitle"
                        >12-week UI skill building for designers</span
                      >
                    </a>
                  </li>
                  <li class="nav-v2-sub__divider"></li>
                  <li class="nav-v2-sub__item">
                    <a
                      class="nav-v2-sub__link"
                      data-nav-event-clicked="Workshops"
                      href="/workshops">
                      Live interactive workshops
                      <span class="nav-v2-sub__subtitle"
                        >with design professionals</span
                      >
                    </a>
                  </li>
                </ul>
              </li>

              <li class="nav-v2-main__item">
                <a data-nav-event-clicked="Jobs" href="/jobs">Jobs</a>
              </li>

              <li class="nav-v2-main__item">
                <a data-nav-event-clicked="Go Pro" href="/pro">Go Pro</a>
              </li>

              <li
                class="nav-v2-main__item nav-v2-main__item--divided nav-v2-hide-medium-up">
                <a data-nav-event-clicked="Sign in" href="/session/new"
                  >Log in</a
                >
              </li>
            </ul>
          </div>
        </nav>

        <a
          class="nav-v2-logo"
          href="/"
          data-nav-event-clicked="Logo"
          aria-label="Back to home page">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="76"
            height="30"
            viewBox="0 0 210 59"
            fill="none"
            class="fill-current">
            <title>Dribbble: the community for graphic design</title>
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M206.622 31.928C207.065 31.4116 207.85 31.4352 208.253 31.986H208.25L209.784 34.0834C210.075 34.4864 210.073 35.0425 209.769 35.4349C207.106 38.8893 202.44 42.2143 196.81 42.5359C192.366 42.7887 188.701 41.1051 186.706 37.9221C186.311 37.2925 185.44 37.2557 184.997 37.8511C182.63 41.0286 179.766 43.5134 176.782 43.6845C171.467 43.9876 169.966 40.4228 171.28 32.563C171.412 31.7805 170.726 31.1192 169.987 31.3141C168.885 31.6065 167.715 31.7356 166.528 31.633C166.034 31.5907 165.571 31.8912 165.422 32.3811C163.455 38.8418 158.774 44.8518 152.715 45.1997C148.847 45.421 143.069 43.205 143.647 33.9462C143.695 33.1927 143.019 32.5999 142.323 32.8106C141.11 33.1795 139.804 33.3534 138.474 33.2401C137.981 33.1979 137.52 33.4983 137.371 33.9885C135.404 40.449 130.723 46.4592 124.664 46.8068C120.796 47.0282 115.018 44.8124 115.596 35.5536C115.644 34.7998 114.968 34.207 114.272 34.418C113.059 34.7869 111.753 34.9634 110.423 34.8473C109.93 34.8053 109.469 35.1057 109.32 35.5956C107.352 42.0564 102.672 48.0664 96.6132 48.4142C93.8613 48.5723 90.1398 47.4945 88.4308 43.5264C88.1016 42.7599 87.1144 42.6438 86.6257 43.3105C84.2334 46.5751 81.3193 49.152 78.2762 49.3259C75.1571 49.505 73.4509 48.2535 72.7091 46.0216C72.4458 45.2339 71.4609 45.0467 70.9293 45.6712C68.8002 48.1744 66.3749 50.0082 63.9216 50.1479C60.1393 50.3666 57.9619 47.563 57.7823 44.1667C57.5747 40.204 59.2887 35.564 61.2025 30.4999C61.4684 29.7964 60.9873 29.0348 60.2608 29.0032C59.157 28.956 57.8963 28.8399 56.7113 28.6185C56.1771 28.5159 55.6583 28.8479 55.5063 29.3907C53.243 37.4716 49.7771 45.392 46.8529 50.074C46.5263 50.5984 45.8505 50.7381 45.3593 50.377L43.1264 48.7331C42.6682 48.393 42.5441 47.7397 42.8504 47.247C47.0759 40.478 50.8278 29.8807 52.1215 22.0421C52.2025 21.5415 52.61 21.17 53.0986 21.141L56.0683 20.9697C56.7493 20.9302 57.2861 21.5652 57.162 22.2634L57.1493 22.3372C57.0379 22.959 57.4532 23.5439 58.0532 23.6257C60.7164 23.992 64.6963 24.0366 67.3975 23.9313C68.157 23.9023 68.6938 24.6875 68.4178 25.4226C66.2507 31.1876 63.3469 39.1765 63.5139 42.3382C63.5899 43.7662 64.2204 44.5462 65.3291 44.4829C67.4508 44.3619 70.7141 40.0959 73.1876 35.3455C73.2331 35.261 73.2659 35.169 73.2862 35.0741C74.1196 31.3543 75.3565 27.2068 76.6061 23.0163L76.6837 22.7561C76.8128 22.3188 77.1901 22.0131 77.6306 21.9868L81.1876 21.7839C81.9219 21.7417 82.4712 22.4795 82.2485 23.2093C82.0654 23.8112 81.883 24.409 81.7023 25.0014C78.5723 35.2603 75.9438 43.8759 79.4838 43.6742C81.7978 43.5422 85.0764 39.6164 87.8966 34.0279C87.9421 33.9356 87.9751 33.8381 87.9954 33.7355C88.1372 33.0055 88.3092 32.2416 88.5195 31.4432C90.1639 24.8753 92.0286 18.3691 93.8955 11.855C94.4717 9.8446 95.0481 7.83341 95.6182 5.81945C95.7449 5.37417 96.1245 5.06062 96.57 5.03426L100.221 4.82611C100.963 4.78396 101.512 5.52962 101.279 6.26474C99.8208 10.8388 98.2967 15.7106 96.8487 20.4006C96.5448 21.3887 97.603 22.2107 98.4386 21.6416C99.8791 20.6562 101.545 20.0027 103.158 19.9105C107.267 19.676 110.064 23.0565 110.332 28.1496C110.347 28.4184 110.363 28.7082 110.37 29.0032C110.385 29.5673 110.808 30.023 111.348 30.0704C113.282 30.2417 115.259 29.6673 116.786 28.3051C116.943 28.1654 117.049 27.9757 117.102 27.7701C118.616 21.8916 120.287 16.0568 121.959 10.2147C122.532 8.21455 123.105 6.21353 123.672 4.20956C123.798 3.76427 124.178 3.45072 124.624 3.42438L128.274 3.21623C129.016 3.17408 129.566 3.91972 129.333 4.65484C127.874 9.22892 126.35 14.1007 124.902 18.7907C124.598 19.7788 125.657 20.6008 126.492 20.0317C127.933 19.0463 129.599 18.3929 131.211 18.3006C135.32 18.0662 138.117 21.4466 138.386 26.5399C138.401 26.8084 138.416 27.0985 138.424 27.3935C138.436 27.9573 138.862 28.4132 139.401 28.4607C141.335 28.6318 143.312 28.0573 144.839 26.6951C144.996 26.5557 145.102 26.3659 145.156 26.1604C146.67 20.2818 148.34 14.4471 150.013 8.6051C150.586 6.60484 151.158 4.60372 151.725 2.59968C151.852 2.15439 152.232 1.84085 152.677 1.8145L156.328 1.60635C157.07 1.56419 157.619 2.30985 157.386 3.04497C155.928 7.61902 154.404 12.4908 152.956 17.1808C152.652 18.1689 153.71 18.991 154.546 18.4219C155.986 17.4364 157.652 16.783 159.265 16.6908C163.374 16.4563 166.171 19.8367 166.44 24.9299C166.455 25.2013 166.47 25.4885 166.477 25.7835C166.493 26.3447 166.913 26.8032 167.452 26.8507C169.323 27.0166 171.237 26.4844 172.741 25.2171C172.908 25.0774 173.024 24.8798 173.08 24.6637C174.804 18.0187 177.336 9.31324 179.777 0.981894C179.906 0.541877 180.285 0.236236 180.726 0.209888L184.344 0.0017367C185.078 -0.0404207 185.627 0.692063 185.407 1.42191C182.047 12.5778 179.308 22.3372 177.797 28.0944C175.789 35.9039 175.711 38.1567 177.994 38.025C179.911 37.9143 182.493 35.1952 184.928 31.0847C185.025 30.924 185.075 30.7397 185.083 30.5526C185.402 22.324 190.447 14.8385 197.946 14.409C202.969 14.1218 205.721 17.916 205.918 21.6495C206.293 28.7767 199.248 33.3324 192.42 32.9107C191.625 32.8606 191.047 33.7145 191.397 34.4574C192.351 36.4967 194.359 37.6352 197.787 37.4374C201.048 37.2531 204.468 34.439 206.622 31.928ZM93.7548 33.9278C92.1345 40.4228 94.1017 42.9652 96.646 42.8203C100.823 42.5805 104.864 34.9263 104.553 29.019C104.416 26.4396 102.907 25.0958 101.145 25.1961C98.2106 25.3646 95.0512 28.745 93.7548 33.9278ZM121.808 32.3207C120.188 38.8154 122.155 41.3581 124.7 41.2131H124.697C128.874 40.9734 132.917 33.3192 132.606 27.4119C132.472 24.8324 130.96 23.4886 129.198 23.5887C126.264 23.7574 123.105 27.1379 121.808 32.3207ZM149.862 30.7133C148.242 37.2082 150.209 39.7509 152.753 39.606H152.751C156.925 39.3662 160.971 31.712 160.66 25.8047C160.525 23.2251 159.014 21.8814 157.252 21.9815C154.318 22.1501 151.158 25.5307 149.862 30.7133ZM200.584 22.2239C200.559 20.5218 199.513 19.2887 197.817 19.3862H197.815C194.483 19.5785 191.875 23.1856 191.045 27.562C190.913 28.2577 191.422 28.9058 192.103 28.8899C196.407 28.7821 200.721 25.9416 200.584 22.2239ZM44.3525 25.3837C43.9171 12.1962 35.3423 3.49339 22.6712 3.94658C17.2307 4.19426 11.0052 6.25733 6.32164 9.9461C5.88113 10.2939 5.76719 10.9315 6.06593 11.4163L8.05331 14.6519C8.39254 15.2052 9.11407 15.3185 9.60776 14.9075C13.1724 11.9459 18.0383 10.0041 22.7193 9.79855C31.403 9.43757 37.7828 14.9971 38.1551 25.7367C38.6209 38.2417 30.2157 52.5461 16.7091 53.3207C16.2382 53.3471 15.7471 53.3577 15.2559 53.3577C14.5673 53.3577 14.0585 52.6858 14.2306 51.9901C16.8357 41.4744 19.8763 30.1974 22.9776 19.7029C23.1928 18.973 22.6459 18.2458 21.9143 18.288L17.9648 18.5146C17.5218 18.5409 17.142 18.8492 17.0129 19.2918C14.0331 29.6045 11.0508 40.7895 8.36723 51.284C8.21279 51.89 7.59761 52.2379 7.02544 52.0427C5.62543 51.566 4.34693 51.0232 3.2583 50.3881C2.73677 50.0825 2.07601 50.2987 1.80765 50.8571L0.11142 54.4037C-0.139216 54.9281 0.0455967 55.5709 0.539275 55.8527C4.38489 58.0345 10.223 59.2806 16.0914 58.9462C35.4032 57.8393 44.864 40.0015 44.3525 25.3889V25.3837ZM82.3044 9.18082C79.955 9.31518 77.8713 11.9553 78.0183 14.7377C78.1143 16.5715 79.2917 17.7967 81.1195 17.694C83.4689 17.5596 85.6106 14.7798 85.4714 12.1318C85.3754 10.298 84.0005 9.08333 82.3044 9.18082Z"
              fill="currentColor"></path>
          </svg>
        </a>

        <div class="nav-v2-dynamic" data-nav-v2-dynamic>
          <div class="nav-v2-dynamic__logged-out">
            <form
              class="nav-v2-search"
              data-nav-v2-search-form
              action="/search">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="17"
                height="17"
                viewBox="0 0 17 17"
                fill="none"
                role="img"
                class="icon nav-v2-search__icon">
                <path
                  d="M1.5 7.75C1.5 9.4076 2.15848 10.9973 3.33058 12.1694C4.50269 13.3415 6.0924 14 7.75 14C9.4076 14 10.9973 13.3415 12.1694 12.1694C13.3415 10.9973 14 9.4076 14 7.75C14 6.0924 13.3415 4.50269 12.1694 3.33058C10.9973 2.15848 9.4076 1.5 7.75 1.5C6.0924 1.5 4.50269 2.15848 3.33058 3.33058C2.15848 4.50269 1.5 6.0924 1.5 7.75V7.75Z"
                  stroke="currentColor"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"></path>
                <path
                  d="M12.814 12.8132L15.5 15.4999"
                  stroke="currentColor"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"></path>
              </svg>

              <input
                class="nav-v2-search__input"
                type="text"
                name="q"
                placeholder="Search..."
                autocomplete="off"
                value="" />
            </form>

            <a
              class="nav-v2-search-btn"
              title="Search"
              data-nav-event-clicked="Search"
              href="/search">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="17"
                height="17"
                viewBox="0 0 17 17"
                fill="none"
                role="img"
                class="icon nav-v2-search-btn__icon">
                <path
                  d="M1.5 7.75C1.5 9.4076 2.15848 10.9973 3.33058 12.1694C4.50269 13.3415 6.0924 14 7.75 14C9.4076 14 10.9973 13.3415 12.1694 12.1694C13.3415 10.9973 14 9.4076 14 7.75C14 6.0924 13.3415 4.50269 12.1694 3.33058C10.9973 2.15848 9.4076 1.5 7.75 1.5C6.0924 1.5 4.50269 2.15848 3.33058 3.33058C2.15848 4.50269 1.5 6.0924 1.5 7.75V7.75Z"
                  stroke="currentColor"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"></path>
                <path
                  d="M12.814 12.8132L15.5 15.4999"
                  stroke="currentColor"
                  stroke-width="1.5"
                  stroke-linecap="round"
                  stroke-linejoin="round"></path>
              </svg>
            </a>

            <a
              class="nav-v2-dynamic__login"
              data-nav-event-clicked="Sign in"
              href="/session/new"
              >Log in</a
            >
            <a
              class="btn2 btn2--medium"
              data-nav-event-clicked="Sign Up"
              href="/signup/new"
              >Sign up</a
            >
          </div>
        </div>
      </div>
    </div>

    <div
      id="g_id_onload"
      data-client_id="32073492121-s6ur8ti01mh34gq2bpbufb8ujdfrpn4v.apps.googleusercontent.com"
      data-login_uri="https://dribbble.com/auth/google_one_tap/callback"
      data-ux_mode="redirect"></div>

    <main class="home-page">
      <section class="hero" data-track-location="Header">
        <div class="home-container">
          <div class="home-badge home-badge--color-cycle">
            <a
              data-track-cta="Get started"
              href="/signup/new?return_to_after_signup=%2Fget-started"
              >Over 3 million ready-to-work creatives!</a
            >
          </div>
          <h1 class="hero__heading">The world’s destination for design</h1>
          <div class="home-type-body-large font-weight-500">
            Get inspired by the work of millions of top-rated designers &
            agencies around the world.
          </div>
          <a
            class="margin-t-32 btn2 btn2--large"
            data-track-cta="Get started"
            href="/signup/new?return_to_after_signup=%2Fget-started"
            >Get started</a
          >
        </div>

        <div class="hero-marquee" style="--card-count: 24">
          <div class="hero-marquee__track">
            <div class="hero-marquee__grid">
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.4218163811660741s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Mercedes Bazan</div>
                  <div div class="hero-marquee-item__title">Illustrator</div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Graphic Design</li>
                    <li class="hero-marquee-item__tag">Illustration</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Mercedes Bazan"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47178/original/mercedes-bazan.png?1689174566&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.6886735852251223s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Victa Wille</div>
                  <div div class="hero-marquee-item__title">
                    Digital Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Mobile</li>
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Victa Wille"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47175/original/1fb34610061a95a007ac5e7b1dc53138.jpeg?1685645183&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.2713989171560739s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Vladimir Gruev</div>
                  <div div class="hero-marquee-item__title">
                    Digital Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">Design</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Vladimir Gruev"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47173/original/Vladimir_Gruev.png?1689174896&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.14960758164355736s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Elif Kameşoğlu</div>
                  <div div class="hero-marquee-item__title">Brand Designer</div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">Illustration</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Elif Kameşoğlu"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47176/original/9b22cd83bde1809976bec0722d1f8923.jpeg?1685645213&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.8503232547200068s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">
                    Aurélien Salomon
                  </div>
                  <div div class="hero-marquee-item__title">
                    Design Director
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Mobile</li>
                    <li class="hero-marquee-item__tag">Product</li>
                    <li class="hero-marquee-item__tag">UX</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Aurélien Salomon"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47170/original/cd3266dde4f00a5d6a509c7375ddaecd.png?1685644840&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.7305560414817464s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Dan Mall</div>
                  <div div class="hero-marquee-item__title">
                    Design Educator
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Product</li>
                    <li class="hero-marquee-item__tag">UX</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <video
                    width="273"
                    height="340"
                    playsinline
                    class="lazyload lazypreload"
                    data-autoplay
                    preload="none"
                    loop
                    muted
                    src="https://cdn.dribbble.com/uploads/47179/original/35d07cfebd303e05e688078015da0cc2.mp4?1685645373" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.1780512573544114s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Jesse Showalter</div>
                  <div div class="hero-marquee-item__title">
                    Design Educator
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Web</li>
                    <li class="hero-marquee-item__tag">Mobile</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <video
                    width="273"
                    height="340"
                    playsinline
                    class="lazyload lazypreload"
                    data-autoplay
                    preload="none"
                    loop
                    muted
                    src="https://cdn.dribbble.com/uploads/47180/original/1def7b9fb30832c4af4353b325d9c3af.mp4?1685645402" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.24588519046355506s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Helen Tran</div>
                  <div div class="hero-marquee-item__title">
                    Lead Product Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Leadership</li>
                    <li class="hero-marquee-item__tag">Product</li>
                    <li class="hero-marquee-item__tag">UX</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <video
                    width="273"
                    height="340"
                    playsinline
                    class="lazyload lazypreload"
                    data-autoplay
                    preload="none"
                    loop
                    muted
                    src="https://cdn.dribbble.com/uploads/47181/original/1e3a73a174484bef522b620c401cd00a.mp4?1685645427" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.5000650952612867s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Andrea Jelić</div>
                  <div div class="hero-marquee-item__title">
                    Digital Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Andrea Jelić"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47172/original/d85ae8c7db2421e9a01ecac942978d4b.png?1685645079&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.2787685246618762s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Lilla Bardenova</div>
                  <div div class="hero-marquee-item__title">
                    Brand + Illustrator
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">Illustration</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Lilla Bardenova"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47174/original/4f02d72fe701b15b2168a4954332427f.png?1685645150&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.5771901982100308s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Daniele Buffa</div>
                  <div div class="hero-marquee-item__title">
                    Principal Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Animation</li>
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Visual</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Daniele Buffa"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47171/original/daniele-buffa-3.png?1689174763&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.9968218559165245s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Chris Owens</div>
                  <div div class="hero-marquee-item__title">
                    Creative Director
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Illustration</li>
                    <li class="hero-marquee-item__tag">Mobile</li>
                    <li class="hero-marquee-item__tag">UI</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Chris Owens"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47177/original/3986915be548424a5d36657f2b034ead.jpeg?1685645250&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.6159750302886903s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Mercedes Bazan</div>
                  <div div class="hero-marquee-item__title">Illustrator</div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Graphic Design</li>
                    <li class="hero-marquee-item__tag">Illustration</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Mercedes Bazan"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47178/original/mercedes-bazan.png?1689174566&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.7826384222517112s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Victa Wille</div>
                  <div div class="hero-marquee-item__title">
                    Digital Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Mobile</li>
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Victa Wille"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47175/original/1fb34610061a95a007ac5e7b1dc53138.jpeg?1685645183&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.12666264128945226s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Vladimir Gruev</div>
                  <div div class="hero-marquee-item__title">
                    Digital Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">Design</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Vladimir Gruev"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47173/original/Vladimir_Gruev.png?1689174896&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.9315996466253146s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Elif Kameşoğlu</div>
                  <div div class="hero-marquee-item__title">Brand Designer</div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">Illustration</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Elif Kameşoğlu"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47176/original/9b22cd83bde1809976bec0722d1f8923.jpeg?1685645213&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.9750153944299333s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">
                    Aurélien Salomon
                  </div>
                  <div div class="hero-marquee-item__title">
                    Design Director
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Mobile</li>
                    <li class="hero-marquee-item__tag">Product</li>
                    <li class="hero-marquee-item__tag">UX</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Aurélien Salomon"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47170/original/cd3266dde4f00a5d6a509c7375ddaecd.png?1685644840&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.05302962489371332s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Dan Mall</div>
                  <div div class="hero-marquee-item__title">
                    Design Educator
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Product</li>
                    <li class="hero-marquee-item__tag">UX</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <video
                    width="273"
                    height="340"
                    playsinline
                    class="lazyload lazypreload"
                    data-autoplay
                    preload="none"
                    loop
                    muted
                    src="https://cdn.dribbble.com/uploads/47179/original/35d07cfebd303e05e688078015da0cc2.mp4?1685645373" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.2970963539181417s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Jesse Showalter</div>
                  <div div class="hero-marquee-item__title">
                    Design Educator
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Web</li>
                    <li class="hero-marquee-item__tag">Mobile</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <video
                    width="273"
                    height="340"
                    playsinline
                    class="lazyload lazypreload"
                    data-autoplay
                    preload="none"
                    loop
                    muted
                    src="https://cdn.dribbble.com/uploads/47180/original/1def7b9fb30832c4af4353b325d9c3af.mp4?1685645402" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.24478139614835115s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Helen Tran</div>
                  <div div class="hero-marquee-item__title">
                    Lead Product Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Leadership</li>
                    <li class="hero-marquee-item__tag">Product</li>
                    <li class="hero-marquee-item__tag">UX</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <video
                    width="273"
                    height="340"
                    playsinline
                    class="lazyload lazypreload"
                    data-autoplay
                    preload="none"
                    loop
                    muted
                    src="https://cdn.dribbble.com/uploads/47181/original/1e3a73a174484bef522b620c401cd00a.mp4?1685645427" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.7915451135914744s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Andrea Jelić</div>
                  <div div class="hero-marquee-item__title">
                    Digital Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Andrea Jelić"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47172/original/d85ae8c7db2421e9a01ecac942978d4b.png?1685645079&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.5800495946599786s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Lilla Bardenova</div>
                  <div div class="hero-marquee-item__title">
                    Brand + Illustrator
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Brand</li>
                    <li class="hero-marquee-item__tag">Illustration</li>
                    <li class="hero-marquee-item__tag">Web</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Lilla Bardenova"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47174/original/4f02d72fe701b15b2168a4954332427f.png?1685645150&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.3309752878798343s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Daniele Buffa</div>
                  <div div class="hero-marquee-item__title">
                    Principal Designer
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Animation</li>
                    <li class="hero-marquee-item__tag">UI</li>
                    <li class="hero-marquee-item__tag">Visual</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Daniele Buffa"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47171/original/daniele-buffa-3.png?1689174763&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
              <div
                class="hero-marquee-item"
                data-lazy-parent
                style="--reveal-delay: 0.022057398565963893s">
                <div div class="hero-marquee-item__info">
                  <div div class="hero-marquee-item__name">Chris Owens</div>
                  <div div class="hero-marquee-item__title">
                    Creative Director
                  </div>

                  <ul class="hero-marquee-item__tags">
                    <li class="hero-marquee-item__tag">Illustration</li>
                    <li class="hero-marquee-item__tag">Mobile</li>
                    <li class="hero-marquee-item__tag">UI</li>
                  </ul>
                </div>

                <div div class="hero-marquee-item__media">
                  <img
                    alt="Chris Owens"
                    width="273"
                    height="340"
                    class="lazyload lazypreload"
                    data-sizes="auto"
                    data-aspectratio="0.8029411764705883"
                    data-src="https://cdn.dribbble.com/uploads/47177/original/3986915be548424a5d36657f2b034ead.jpeg?1685645250&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <div class="home-feed">
        <h2 class="home-feed__heading home-container">
          Explore inspiring designs
        </h2>

        <ol
          class="js-thumbnail-grid shots-grid group dribbbles container-fluid">
          <li
            id="screenshot-24417888"
            data-thumbnail-id="24417888"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble video"
              data-video-teaser-small="https://cdn.dribbble.com/userupload/15292209/file/small-12a7d3e48b7fdc1252f6a6b7b536e517.mp4"
              data-video-teaser-medium="https://cdn.dribbble.com/userupload/15292209/file/large-582d5af1bf09e09c653b8727ffbb5552.mp4"
              data-video-teaser-large="https://cdn.dribbble.com/userupload/15292209/file/large-582d5af1bf09e09c653b8727ffbb5552.mp4"
              data-video-teaser-original="https://cdn.dribbble.com/userupload/15292209/file/original-31affadec2d1174d45dcd627d631ab98.mp4">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="A Greek moment 🇬🇷 3d animation architecture c4d characterdesign characters cinema4d goat greece greek house illustration redshift traditional travel village"
                  data-srcset="https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15292209/file/still-6273f93ed581484d34fec1a438671c9c.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras">
                <div
                  class="loading-indicator shot-thumbnail-extras-icon disable-media-icons"></div>

                <a
                  class="animated-target"
                  href="/shots/24417888-A-Greek-moment">
                  <span class="accessibility-text">Shot Link</span>
                </a>
              </div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24417888"
                href="/shots/24417888-A-Greek-moment">
                <span class="accessibility-text">View A Greek moment 🇬🇷</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">A Greek moment 🇬🇷</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24417888 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="330915"
                  href="/guillaumekurkdjian">
                  <img
                    class="photo lazyload"
                    alt="Guillaume Kurkdjian"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/330915/avatars/small/f27402d0fcab80d8b369e7fee1151348.jpg?1719399708"
                    src="" />
                  <span class="display-name">Guillaume Kurkdjian</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24417888 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    336
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    63.6k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24419663"
            data-thumbnail-id="24419663"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Skull House architecture branding design digital editorial ethereum front icon illustration indonesia logo minimal nft opensea play skeleton skull vector view"
                  data-srcset="https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15297532/file/original-8a123a21e6b920a5ce07ac9e08585fb1.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras">
                <div class="is-rebound shot-thumbnail-extras-icon">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon">
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M0 8C0 12.4183 3.58172 16 8 16C12.4183 16 16 12.4183 16 8C16 3.58172 12.4183 0 8 0C3.58172 0 0 3.58172 0 8ZM8.16504 6.24902V5.06161C8.16585 4.89576 8.09142 4.73031 7.94336 4.60411C7.64766 4.35128 7.16872 4.35128 6.87302 4.60411L3.31087 7.6505L6.87302 10.6969C7.02107 10.8231 7.21443 10.8866 7.40819 10.8866C7.60195 10.8866 7.79531 10.8235 7.94336 10.6969C8.09142 10.5707 8.16585 10.4048 8.16504 10.2394V8.98145C10.8239 9.1121 12.2102 10.7855 12.2102 10.7855C12.2102 8.0174 10.5161 6.43227 8.16504 6.24902Z"
                      fill="white"></path>
                  </svg>
                </div>
              </div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24419663"
                href="/shots/24419663-Skull-House">
                <span class="accessibility-text">View Skull House</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Skull House</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24419663 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="22815"
                  href="/tommychandra">
                  <img
                    class="photo lazyload"
                    alt="Tommy Chandra"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/22815/avatars/small/c5d84e558afc03acefb69aa010553fe4.jpg?1631871725"
                    src="" />
                  <span class="display-name">Tommy Chandra</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24419663 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    99
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    33.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-23262650"
            data-thumbnail-id="23262650"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Sours &amp; Cobblers 2d bar beverage clover club cobbler coupe digital painting drink garnish glass illustration martender martini micology raspberry retro sour speak easy vintage"
                  data-srcset="https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/11973895/file/original-298803cb45251cd4255d83afd0a9584c.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="23262650"
                href="/shots/23262650-Sours-Cobblers">
                <span class="accessibility-text"
                  >View Sours &amp; Cobblers</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Sours &amp; Cobblers</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-23262650 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="650400"
                  href="/nicetriangle">
                  <img
                    class="photo lazyload"
                    alt="Isaac LeFever"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/650400/avatars/small/eea38ecb25370aa56b4e1123838fba3d.jpg?1717171225"
                    src="" />
                  <span class="display-name">Isaac LeFever</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-23262650 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    164
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    49.5k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24424886"
            data-thumbnail-id="24424886"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="🚨 Procreate Brush 🚨 amplitude anatomy brush brushes crest dot drawing environment grain illustration landscape pack procreate series stipple stippling texture trough wave wavelength"
                  data-srcset="https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15312934/file/original-50ef03c31e74b3983ea602a863e90b3b.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24424886"
                href="/shots/24424886--Procreate-Brush">
                <span class="accessibility-text"
                  >View 🚨 Procreate Brush 🚨</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">🚨 Procreate Brush 🚨</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24424886 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="250507"
                  href="/bradhansen">
                  <img
                    class="photo lazyload"
                    alt="Brad Hansen"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/250507/avatars/small/9d2da90d672f53bd1950c66dbf3140f8.jpg?1672274449"
                    src="" />
                  <span class="display-name">Brad Hansen</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24424886 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    103
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    28.8k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24412489"
            data-thumbnail-id="24412489"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt='"Call Me Maybe" - NFT art adobe illustrator blue cocktail contrast daily art design digital art flat design flower illustration minimalism nft phone retro stylized vector vector illustration'
                  data-srcset="https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15276180/file/original-9c6822b6c20c06a586a0072d56ba4ed1.jpg?crop=0x137-1889x1554&amp;resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24412489"
                href="/shots/24412489--Call-Me-Maybe-NFT-art">
                <span class="accessibility-text"
                  >View &quot;Call Me Maybe&quot; - NFT art</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">
                    &quot;Call Me Maybe&quot; - NFT art
                  </div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24412489 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="3562273"
                  href="/designbyangie">
                  <img
                    class="photo lazyload"
                    alt="Angie Mathot"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3562273/avatars/small/009cf8adb22b0a7bf3c659de98b6760e.jpg?1717059390"
                    src="" />
                  <span class="display-name">Angie Mathot</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24412489 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    230
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    52.7k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24445662"
            data-thumbnail-id="24445662"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Johnny cash characters collage country music people retro style styletest vector website"
                  data-srcset="https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15375506/file/original-f467810de74daa65aaf18f0a43b0451b.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24445662"
                href="/shots/24445662-Johnny-cash">
                <span class="accessibility-text">View Johnny cash</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Johnny cash</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24445662 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1052957"
                  href="/jonesandcompany">
                  <img
                    class="photo lazyload"
                    alt="JONES&amp;CO"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1052957/avatars/small/63c4ceb76b6911247231c63187c6d57e.png?1634035666"
                    src="" />
                  <span class="display-name">JONES&amp;CO</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24445662 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    23
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    5.1k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24406546"
            data-thumbnail-id="24406546"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Summer Aesthetic Illustrations abobe illustrator adidas adobe bikini carver design drawing flowers graphic design hand drawn illustration ipad olipop passion fruit procreate shoes skateboard summer sunglases tennis"
                  data-srcset="https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15259505/file/original-5bfd341ceeb21fa1bb5209edd2266c79.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24406546"
                href="/shots/24406546-Summer-Aesthetic-Illustrations">
                <span class="accessibility-text"
                  >View Summer Aesthetic Illustrations</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Summer Aesthetic Illustrations</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24406546 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1445288"
                  href="/debbietrout">
                  <img
                    class="photo lazyload"
                    alt="Debbie Trout"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1445288/avatars/small/413c2e8f60a05d3a4b0d3141c34fcbb3.jpg?1639365538"
                    src="" />
                  <span class="display-name">Debbie Trout</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24406546 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    183
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    41.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24406768"
            data-thumbnail-id="24406768"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="The Archer archery branding charleston illustration lockup logo restaurant script south carolina typography"
                  data-srcset="https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15260166/file/original-318cc256f6c42eb70cb27f4346fca69b.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24406768"
                href="/shots/24406768-The-Archer">
                <span class="accessibility-text">View The Archer</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">The Archer</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24406768 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="52084"
                  href="/WOLF_STEVE">
                  <img
                    class="photo lazyload"
                    alt="Steve Wolf"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/52084/avatars/small/692992651656234d8bddb5823a090f98.jpg?1510596786"
                    src="" />
                  <span class="display-name">Steve Wolf</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24406768 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    472
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    83.8k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24431286"
            data-thumbnail-id="24431286"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Los Angeles Rams adobe americanfootball editorial illustration football illustration illustrator la losangeles muti nfl plamtree rams sea sports texture vector"
                  data-srcset="https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15331576/file/original-38d6015485de1a0c5302576e584addc9.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24431286"
                href="/shots/24431286-Los-Angeles-Rams">
                <span class="accessibility-text">View Los Angeles Rams</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Los Angeles Rams</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24431286 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="59947"
                  href="/studioMUTI">
                  <img
                    class="photo lazyload"
                    alt="MUTI"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/59947/avatars/small/5ed2865a861fcd2bc9f9d9aff7600f8b.jpg?1574070463"
                    src="" />
                  <span class="display-name">MUTI</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24431286 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    174
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    34.8k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24427249"
            data-thumbnail-id="24427249"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Straight Bourbon bourbon branding design filigree graphic design illustration label lettering logo ornate packaging typography whiskey woodcut"
                  data-srcset="https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15320424/file/original-4113b0acd56020c583ce32f0a00652ca.jpg?crop=221x463-2079x1857&amp;resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24427249"
                href="/shots/24427249-Straight-Bourbon">
                <span class="accessibility-text">View Straight Bourbon</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Straight Bourbon</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24427249 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="3902"
                  href="/prettyuglydesign">
                  <img
                    class="photo lazyload"
                    alt="Ben Didier"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3902/avatars/small/eb51375faf008c355b83c82ec578a2e5.jpg?1672331087"
                    src="" />
                  <span class="display-name">Ben Didier</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24427249 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    130
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    18.5k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24426644"
            data-thumbnail-id="24426644"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Heyo Summer beach branding character character design collage design figma illustration minimal people portrait summer vector yellow"
                  data-srcset="https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15318577/file/original-61d9475c209eabb84c581e1934879cf2.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24426644"
                href="/shots/24426644-Heyo-Summer">
                <span class="accessibility-text">View Heyo Summer</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Heyo Summer</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24426644 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1119092"
                  href="/teamheyo">
                  <img
                    class="photo lazyload"
                    alt="Heyo"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/414979/avatars/small/6a3fb4b20c29dce831a74dc7dbf591c4.png?1695741732"
                    src="" />
                  <span class="display-name">Heyo</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-team">Team</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24426644 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    222
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    24k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24411841"
            data-thumbnail-id="24411841"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt='Logo concept for "Nashe Mesto" 1930s branding cartoon character character chicken illustration logo vintage'
                  data-srcset="https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15274150/file/original-e7465f315905dce71bda50342d1885d0.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24411841"
                href="/shots/24411841-Logo-concept-for-Nashe-Mesto">
                <span class="accessibility-text"
                  >View Logo concept for &quot;Nashe Mesto&quot;</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">
                    Logo concept for &quot;Nashe Mesto&quot;
                  </div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24411841 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="3113663"
                  href="/Ovcharka">
                  <img
                    class="photo lazyload"
                    alt="OVCHARKA INDUSTRIES"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3113663/avatars/small/dcbf1db5e3d7b105ddad162aec88279d.jpg?1671115528"
                    src="" />
                  <span class="display-name">OVCHARKA INDUSTRIES</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24411841 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    240
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    52.5k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24429008"
            data-thumbnail-id="24429008"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Strawberry mood app berry character digital illustration mood strawberry summer summertime women"
                  data-srcset="https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15325327/file/original-638556fcaec240a249ac007c505dd6c7.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24429008"
                href="/shots/24429008-Strawberry-mood">
                <span class="accessibility-text">View Strawberry mood</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Strawberry mood</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24429008 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1629266"
                  href="/marymaka">
                  <img
                    class="photo lazyload"
                    alt="Mary Maka"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1629266/avatars/small/542236023d877a5b38e351ece1530f1d.jpg?1701344489"
                    src="" />
                  <span class="display-name">Mary Maka</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24429008 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    134
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    25.1k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24445515"
            data-thumbnail-id="24445515"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="❤️ applepencil illustration ipadpro procreate sketch sketchbook"
                  data-srcset="https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15375066/file/original-b49d257144657e04c7f04ca4b62e5c2f.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24445515"
                href="/shots/24445515-">
                <span class="accessibility-text">View ❤️</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">❤️</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24445515 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1037"
                  href="/rikcat">
                  <img
                    class="photo lazyload"
                    alt="Rik Catlow"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1037/avatars/small/845ff4b0089438c6518f392d59f55b1f.png?1673276678"
                    src="" />
                  <span class="display-name">Rik Catlow</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24445515 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    88
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    7.6k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24445268"
            data-thumbnail-id="24445268"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Stargate badge alien badge branding city design galaxy graphic design icon icon set illustration movie portal pyramid scfy space stargate travel universe vector world"
                  data-srcset="https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15374339/file/original-e02857dc01451814985f0f50d08fd78a.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24445268"
                href="/shots/24445268-Stargate-badge">
                <span class="accessibility-text">View Stargate badge</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Stargate badge</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24445268 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="458522"
                  href="/almigor">
                  <img
                    class="photo lazyload"
                    alt="Aleksandar Savic  / almigor"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/458522/avatars/small/07b9b0f65924ef9cfffa9c7ad6b03fc7.png?1665138088"
                    src="" />
                  <span class="display-name">Aleksandar Savic / almigor</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24445268 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    132
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    14.5k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24415419"
            data-thumbnail-id="24415419"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Handle with Care branding illustration illustrator inflate packaging the creative pain vector"
                  data-srcset="https://cdn.dribbble.com/userupload/15285178/file/original-c45fafe0d2d969d3d7d6b6582e29f69c.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15285178/file/original-c45fafe0d2d969d3d7d6b6582e29f69c.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15285178/file/original-c45fafe0d2d969d3d7d6b6582e29f69c.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15285178/file/original-c45fafe0d2d969d3d7d6b6582e29f69c.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15285178/file/original-c45fafe0d2d969d3d7d6b6582e29f69c.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15285178/file/original-c45fafe0d2d969d3d7d6b6582e29f69c.png?resize=800x600&amp;vertical=center 800w"
                  data-src="https://cdn.dribbble.com/userupload/15285178/file/original-c45fafe0d2d969d3d7d6b6582e29f69c.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24415419"
                href="/shots/24415419-Handle-with-Care">
                <span class="accessibility-text">View Handle with Care</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Handle with Care</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24415419 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="508142"
                  href="/thecreativepain">
                  <img
                    class="photo lazyload"
                    alt="Tyler Pate"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/508142/avatars/small/1cffa29a3f16e934e3b310ce18ad2c6d.jpg?1696372002"
                    src="" />
                  <span class="display-name">Tyler Pate</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24415419 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    129
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    27.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24443101"
            data-thumbnail-id="24443101"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble video"
              data-video-teaser-small="https://cdn.dribbble.com/userupload/15368433/file/small-a3816c94ac369f7f977bacde57fa1a8b.mp4"
              data-video-teaser-medium="https://cdn.dribbble.com/userupload/15368433/file/large-4ced64baef3ccea5419159653eebcb54.mp4"
              data-video-teaser-large="https://cdn.dribbble.com/userupload/15368433/file/large-4ced64baef3ccea5419159653eebcb54.mp4"
              data-video-teaser-original="https://cdn.dribbble.com/userupload/15368433/file/original-8efe75c9d8fbf39f9a8421430ec6c3c8.mp4">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Weather animation book branding design fashion illustration interface news slide ui video web"
                  data-srcset="https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15368433/file/still-92fe863f0cbd64f6e2b8001f6cc5b207.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras">
                <div
                  class="loading-indicator shot-thumbnail-extras-icon disable-media-icons"></div>

                <a class="animated-target" href="/shots/24443101-Weather">
                  <span class="accessibility-text">Shot Link</span>
                </a>
              </div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24443101"
                href="/shots/24443101-Weather">
                <span class="accessibility-text">View Weather</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Weather</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24443101 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="203446"
                  href="/GeexArts">
                  <img
                    class="photo lazyload"
                    alt="Geex Arts"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1832625/avatars/small/d0a819596a87076630326f81799e85c0.jpg?1586442553"
                    src="" />
                  <span class="display-name">Geex Arts</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-team">Team</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24443101 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    260
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    17.1k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24445741"
            data-thumbnail-id="24445741"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Elusive Fire Logo System brand design brand identity branding branding design cbd classic fire flame hand drawn identity design illustration logo logo design logodesign masculine phoenix retro typography vintage visual identity"
                  data-srcset="https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15375744/file/original-166292111aeff311cee59aca254a19ff.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24445741"
                href="/shots/24445741-Elusive-Fire-Logo-System">
                <span class="accessibility-text"
                  >View Elusive Fire Logo System</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Elusive Fire Logo System</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24445741 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="3365798"
                  href="/coric_design">
                  <img
                    class="photo lazyload"
                    alt="Coric Design"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3365798/avatars/small/27142d0984a19231593be35a9972bbc4.jpg?1673891024"
                    src="" />
                  <span class="display-name">Coric Design</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24445741 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    74
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    8.6k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24427951"
            data-thumbnail-id="24427951"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Quell Wordmark Logo Concepts art supplies artist brand brand designer branding lettering ligature logo logo concepts logo designer logo sketches logotype quell script type typography wells wells collins wordmark"
                  data-srcset="https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15322610/file/original-988c074c1ad4120a9c50a5b8f82d9043.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24427951"
                href="/shots/24427951-Quell-Wordmark-Logo-Concepts">
                <span class="accessibility-text"
                  >View Quell Wordmark Logo Concepts</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Quell Wordmark Logo Concepts</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24427951 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="77241"
                  href="/wellscollins">
                  <img
                    class="photo lazyload"
                    alt="Wells Collins"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/77241/avatars/small/e3a0069803b02cfdb3cb9031ecd3b12e.jpg?1599151966"
                    src="" />
                  <span class="display-name">Wells Collins</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24427951 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    152
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    20k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24436684"
            data-thumbnail-id="24436684"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Poseidon sea wine label branding grape wine illustration wine вино"
                  data-srcset="https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15347993/file/original-fbdb2345c706a6e30d97e66853bde721.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24436684"
                href="/shots/24436684-Poseidon-sea-wine-label">
                <span class="accessibility-text"
                  >View Poseidon sea wine label</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Poseidon sea wine label</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24436684 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1094383"
                  href="/marcato">
                  <img
                    class="photo lazyload"
                    alt="Marcato Studio"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3020225/avatars/small/dca621eb9a63cba93a93bb0105958185.png?1579079964"
                    src="" />
                  <span class="display-name">Marcato Studio</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-team">Team</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24436684 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    48
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    11.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24432198"
            data-thumbnail-id="24432198"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Simms Fishing Apparel Design apparel design badge design bass bass fishing branding custom lettering custom type fly fishing hat design heritage illustration lettering logo design logo designer retro simms fishing t shirt design trout vintage"
                  data-srcset="https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15334226/file/original-2352ee98ea5792285deb0f2a63b5f163.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24432198"
                href="/shots/24432198-Simms-Fishing-Apparel-Design">
                <span class="accessibility-text"
                  >View Simms Fishing Apparel Design</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Simms Fishing Apparel Design</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24432198 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="46461"
                  href="/Kevkrone">
                  <img
                    class="photo lazyload"
                    alt="Kevin Kroneberger"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/46461/avatars/small/64c8e620627620831be5c86680538158.jpg?1441302604"
                    src="" />
                  <span class="display-name">Kevin Kroneberger</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24432198 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    133
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    24.7k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24412845"
            data-thumbnail-id="24412845"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Illustration [ work in progress ] adline brassai fish graphic design illustration sea szende vector water woman"
                  data-srcset="https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15277335/file/original-a14f63868863bde8511fdc0bdae46060.jpg?crop=1003x1228-2350x2238&amp;resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24412845"
                href="/shots/24412845-Illustration-work-in-progress">
                <span class="accessibility-text"
                  >View Illustration [ work in progress ]</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">
                    Illustration [ work in progress ]
                  </div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24412845 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="79978"
                  href="/szendebrassai">
                  <img
                    class="photo lazyload"
                    alt="Szende Brassai "
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/79978/avatars/small/44a19a36ec2e56e47f59096c2781f37d.png?1478106185"
                    src="" />
                  <span class="display-name">Szende Brassai </span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24412845 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    150
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    45.3k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24427545"
            data-thumbnail-id="24427545"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Here Lies Sal boston branding character character design fire flame flat grave halloween hat illustration illustrator skeleton skull suit vector vector art"
                  data-srcset="https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15321451/file/original-7c57148c4ebe9f3a4f629082c4a1a380.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24427545"
                href="/shots/24427545-Here-Lies-Sal">
                <span class="accessibility-text">View Here Lies Sal</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Here Lies Sal</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24427545 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="35810"
                  href="/bonehaus">
                  <img
                    class="photo lazyload"
                    alt="Kirk! Wallace"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/35810/avatars/small/505cc3dd31384386870f959cf27bf347.jpeg?1708702439"
                    src="" />
                  <span class="display-name">Kirk! Wallace</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24427545 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    94
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    18.6k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24408454"
            data-thumbnail-id="24408454"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="腐った book cartoon cd character cover design graphic design illustration music retro texture tiger vector vintage vinyl"
                  data-srcset="https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=800x600&amp;vertical=center 800w"
                  data-src="https://cdn.dribbble.com/userupload/15265336/file/original-c27f3f00a6d34ad52dc982823844783d.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24408454"
                href="/shots/24408454-">
                <span class="accessibility-text">View 腐った</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">腐った</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24408454 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="289158"
                  href="/elstitch">
                  <img
                    class="photo lazyload"
                    alt="Manuel Cetina "
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/289158/avatars/small/6d51c314867299c1de2524b6b025802e.jpg?1705016347"
                    src="" />
                  <span class="display-name">Manuel Cetina </span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24408454 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    174
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    48.1k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24414067"
            data-thumbnail-id="24414067"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="PlayTech branding budget cloud coin credit debit dollar finance growth healthcare human icon illustration message money playful privacy security smile talk"
                  data-srcset="https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15281385/file/original-f640f776da193d4ec22261abc50eca48.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24414067"
                href="/shots/24414067-PlayTech">
                <span class="accessibility-text">View PlayTech</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">PlayTech</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24414067 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="331579"
                  href="/joshwarren">
                  <img
                    class="photo lazyload"
                    alt="Josh Warren"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/331579/avatars/small/b68b19a0c33efc0048ae80f9dd40789c.jpg?1551218217"
                    src="" />
                  <span class="display-name">Josh Warren</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24414067 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    237
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    48.1k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24446554"
            data-thumbnail-id="24446554"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Nuclear Blast Records design drawing esp floral florals guitar illustration metal nuclear blast records rock rose skull skulls tattoo"
                  data-srcset="https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=800x600&amp;vertical=center 800w"
                  data-src="https://cdn.dribbble.com/userupload/15378478/file/original-a0a606d3852598f9700ae9f3eb3a77f1.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24446554"
                href="/shots/24446554-Nuclear-Blast-Records">
                <span class="accessibility-text"
                  >View Nuclear Blast Records</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Nuclear Blast Records</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24446554 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="77553"
                  href="/samdunn">
                  <img
                    class="photo lazyload"
                    alt="Sam Dunn"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/77553/avatars/small/_.jpg?1389134465"
                    src="" />
                  <span class="display-name">Sam Dunn</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24446554 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    48
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    9.1k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24432958"
            data-thumbnail-id="24432958"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Houses_3 abstract design illustration zutto"
                  data-srcset="https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15337098/file/original-74a7449abc4cce331c6a84e383c889d4.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24432958"
                href="/shots/24432958-Houses-3">
                <span class="accessibility-text">View Houses_3</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Houses_3</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24432958 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="78464"
                  href="/zuttoworld">
                  <img
                    class="photo lazyload"
                    alt="Alexandra Zutto"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/78464/avatars/small/a9ae6a559ab479d179e8bd22591e4028.jpg?1465908886"
                    src="" />
                  <span class="display-name">Alexandra Zutto</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24432958 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    98
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    10.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24432587"
            data-thumbnail-id="24432587"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Shape Studies: 056 abstract bauhaus blue flat geometric geometry gestalt illustration midcentury minimal modernist negative space pattern primary colors rectangle red shapes simple texture vector"
                  data-srcset="https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15335470/file/original-ae1d0c718e3bce525f98e323441474d7.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24432587"
                href="/shots/24432587-Shape-Studies-056">
                <span class="accessibility-text">View Shape Studies: 056</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Shape Studies: 056</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24432587 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="932465"
                  href="/raydaklam">
                  <img
                    class="photo lazyload"
                    alt="Ray Dak Lam"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/932465/avatars/small/973bd8cee80590f03ded32e843020710.png?1631119421"
                    src="" />
                  <span class="display-name">Ray Dak Lam</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24432587 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    156
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    26.5k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24427235"
            data-thumbnail-id="24427235"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Wood Fired Shirt branding drawing illustration lettering merchandise t shirt type typography"
                  data-srcset="https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15320391/file/original-28789540e847d0e0376b72f77bd0f0be.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24427235"
                href="/shots/24427235-Wood-Fired-Shirt">
                <span class="accessibility-text">View Wood Fired Shirt</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Wood Fired Shirt</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24427235 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="189099"
                  href="/danielpatrick">
                  <img
                    class="photo lazyload"
                    alt="Daniel Patrick"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/189099/avatars/small/33b8226ffe6f52701d9c38dba66e0c3e.jpg?1665001754"
                    src="" />
                  <span class="display-name">Daniel Patrick</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24427235 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    73
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    13.6k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24426533"
            data-thumbnail-id="24426533"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Moon Shine - The Cowboy &amp; The Coyote colter wall country music cowboy cowboy hat coyote desert ian tyson label liquor liquor packaging moon moonshine music packaging rye southwestern western whiskey whiskey label whiskey packaging"
                  data-srcset="https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15318256/file/original-97215af984340e907548a5abf8bec3ae.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24426533"
                href="/shots/24426533-Moon-Shine-The-Cowboy-The-Coyote">
                <span class="accessibility-text"
                  >View Moon Shine - The Cowboy &amp; The Coyote</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">
                    Moon Shine - The Cowboy &amp; The Coyote
                  </div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24426533 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="276778"
                  href="/theonlymark">
                  <img
                    class="photo lazyload"
                    alt="Mark Johnston"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/276778/avatars/small/8ca30b0f62b4cfb2a34a4b6a60144fff.jpg?1708536637"
                    src="" />
                  <span class="display-name">Mark Johnston</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24426533 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    134
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    28.7k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24201624"
            data-thumbnail-id="24201624"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Light house beach illustration illustrator light house ocean the creative pain vector"
                  data-srcset="https://cdn.dribbble.com/userupload/14665180/file/original-8fb0ead254e8524499cd8da51c147d89.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/14665180/file/original-8fb0ead254e8524499cd8da51c147d89.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/14665180/file/original-8fb0ead254e8524499cd8da51c147d89.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/14665180/file/original-8fb0ead254e8524499cd8da51c147d89.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/14665180/file/original-8fb0ead254e8524499cd8da51c147d89.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/14665180/file/original-8fb0ead254e8524499cd8da51c147d89.jpg?resize=800x600&amp;vertical=center 800w"
                  data-src="https://cdn.dribbble.com/userupload/14665180/file/original-8fb0ead254e8524499cd8da51c147d89.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24201624"
                href="/shots/24201624-Light-house">
                <span class="accessibility-text">View Light house</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Light house</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24201624 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="508142"
                  href="/thecreativepain">
                  <img
                    class="photo lazyload"
                    alt="Tyler Pate"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/508142/avatars/small/1cffa29a3f16e934e3b310ce18ad2c6d.jpg?1696372002"
                    src="" />
                  <span class="display-name">Tyler Pate</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24201624 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    106
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    21.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24443823"
            data-thumbnail-id="24443823"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Hermit Hermes animal architecture blockchain build crab design digital front house icon illustration logo minimal nft pink snail steampunk tezos vector wing"
                  data-srcset="https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15370344/file/original-fbe2599e970ece6e96fc79fcfe8cdc28.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24443823"
                href="/shots/24443823-Hermit-Hermes">
                <span class="accessibility-text">View Hermit Hermes</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Hermit Hermes</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24443823 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="22815"
                  href="/tommychandra">
                  <img
                    class="photo lazyload"
                    alt="Tommy Chandra"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/22815/avatars/small/c5d84e558afc03acefb69aa010553fe4.jpg?1631871725"
                    src="" />
                  <span class="display-name">Tommy Chandra</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24443823 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    35
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    6.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24410947"
            data-thumbnail-id="24410947"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Gorilla Surf board color fun gorilla hot illustration logo nature pattern sport summer sun surf water wave"
                  data-srcset="https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15271781/file/original-64fc3fc54d9dcdb98e29fe4729991e7b.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24410947"
                href="/shots/24410947-Gorilla-Surf">
                <span class="accessibility-text">View Gorilla Surf</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Gorilla Surf</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24410947 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="74401"
                  href="/Stevan">
                  <img
                    class="photo lazyload"
                    alt="Stevan Rodic"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/74401/avatars/small/STEVA_konstantan_200_X_200_PX.gif?1398280495"
                    src="" />
                  <span class="display-name">Stevan Rodic</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24410947 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    160
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    51.5k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24220676"
            data-thumbnail-id="24220676"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Risotto Branding bento branding colorful homepage illustration jonathan holt oakland san francisco web design"
                  data-srcset="https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/14719090/file/original-f23ed57c7f52ac2c8c92956ff44801a7.png?crop=0x0-1600x1200&amp;resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24220676"
                href="/shots/24220676-Risotto-Branding">
                <span class="accessibility-text">View Risotto Branding</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Risotto Branding</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24220676 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1411165"
                  href="/Jonathan_Holt">
                  <img
                    class="photo lazyload"
                    alt="Jonathan Holt"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1411165/avatars/small/9db892f2a79cc715f200107607657fd4.png?1719596607"
                    src="" />
                  <span class="display-name">Jonathan Holt</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24220676 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    154
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    25k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24429112"
            data-thumbnail-id="24429112"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="J.W.Lees - Pub Signs artwork beer brewery design graphic design illustration irish poster pub sign stamp typography vintage"
                  data-srcset="https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15325615/file/original-d3f5d6e5abb6ca89db0b1b627e249ddf.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24429112"
                href="/shots/24429112-J-W-Lees-Pub-Signs">
                <span class="accessibility-text"
                  >View J.W.Lees - Pub Signs</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">J.W.Lees - Pub Signs</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24429112 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="340292"
                  href="/Widakk">
                  <img
                    class="photo lazyload"
                    alt="Srdjan Vidakovic"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/340292/avatars/small/71a1136ce3f23ccfd16eef21518d9dd7.jpg?1600259810"
                    src="" />
                  <span class="display-name">Srdjan Vidakovic</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24429112 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    122
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    30.2k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24411866"
            data-thumbnail-id="24411866"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Give me the money! cartoon cat character freelance illustration illustrator sticker vector"
                  data-srcset="https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15274221/file/original-5597f1111854b24f2adee28ea160e510.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24411866"
                href="/shots/24411866-Give-me-the-money">
                <span class="accessibility-text">View Give me the money!</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Give me the money!</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24411866 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="488314"
                  href="/Enisaurus">
                  <img
                    class="photo lazyload"
                    alt="Enisaurus"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/488314/avatars/small/53daa2516579204895c83255932f63e6.png?1605170548"
                    src="" />
                  <span class="display-name">Enisaurus</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24411866 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    182
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    44.8k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24426803"
            data-thumbnail-id="24426803"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="First Notion • Sleek Traditional Apparel Collection apparel apparel graphics bold clean logos branding custom branding custom merch influencer merch logo logo with tree merch merch designer nature new merch line outdoor branding simple clean small business logo streetwear vintage apparel designs visual identity design youtuber merch"
                  data-srcset="https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15319114/file/original-570ff1cd44ef1451e66e377fa52aab66.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24426803"
                href="/shots/24426803-First-Notion-Sleek-Traditional-Apparel-Collection">
                <span class="accessibility-text"
                  >View First Notion • Sleek Traditional Apparel
                  Collection</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">
                    First Notion • Sleek Traditional Apparel Collection
                  </div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24426803 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="2328253"
                  href="/VanguardDesignCo">
                  <img
                    class="photo lazyload"
                    alt="Nick Stewart"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/2328253/avatars/small/4cdd0fd9992c903748242f040183e7bf.jpg?1714687770"
                    src="" />
                  <span class="display-name">Nick Stewart</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24426803 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    89
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    22.6k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24396982"
            data-thumbnail-id="24396982"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Cinque Terre Colorful Buildings architecture art buildings colorful europe flat home house illustration illustrator italy location palm sunny"
                  data-srcset="https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15231048/file/original-2feb8a888991af5f14c2556f54d2dd8e.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24396982"
                href="/shots/24396982-Cinque-Terre-Colorful-Buildings">
                <span class="accessibility-text"
                  >View Cinque Terre Colorful Buildings</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Cinque Terre Colorful Buildings</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24396982 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="3863141"
                  href="/irene_neyman">
                  <img
                    class="photo lazyload"
                    alt="Irene Neyman"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3863141/avatars/small/f6119cef35c0aa5f6c1ca8b4c68eeece.png?1717106116"
                    src="" />
                  <span class="display-name">Irene Neyman</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24396982 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    67
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    8.5k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24398955"
            data-thumbnail-id="24398955"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="We are Family character child couple family health illustration insurance line love spot illustration ui vector"
                  data-srcset="https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15237231/file/original-0b108da73a608afecd084b0e3c4ef6cb.png?crop=85x39-1689x1242&amp;resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24398955"
                href="/shots/24398955-We-are-Family">
                <span class="accessibility-text">View We are Family</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">We are Family</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24398955 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="760333"
                  href="/makers_co">
                  <img
                    class="photo lazyload"
                    alt="Makers Company"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/760333/avatars/small/0018b5b654ce97c8112f386d6ad722b5.png?1676926316"
                    src="" />
                  <span class="display-name">Makers Company</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24398955 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    213
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    44.3k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24400848"
            data-thumbnail-id="24400848"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Lotus Flower engraving etching flower illustration line art print scratchboard woodcut"
                  data-srcset="https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15243264/file/original-eb527e4736c1c98e64f865d8213c6552.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras">
                <div class="is-rebound shot-thumbnail-extras-icon">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon">
                    <path
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      d="M0 8C0 12.4183 3.58172 16 8 16C12.4183 16 16 12.4183 16 8C16 3.58172 12.4183 0 8 0C3.58172 0 0 3.58172 0 8ZM8.16504 6.24902V5.06161C8.16585 4.89576 8.09142 4.73031 7.94336 4.60411C7.64766 4.35128 7.16872 4.35128 6.87302 4.60411L3.31087 7.6505L6.87302 10.6969C7.02107 10.8231 7.21443 10.8866 7.40819 10.8866C7.60195 10.8866 7.79531 10.8235 7.94336 10.6969C8.09142 10.5707 8.16585 10.4048 8.16504 10.2394V8.98145C10.8239 9.1121 12.2102 10.7855 12.2102 10.7855C12.2102 8.0174 10.5161 6.43227 8.16504 6.24902Z"
                      fill="white"></path>
                  </svg>
                </div>
              </div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24400848"
                href="/shots/24400848-Lotus-Flower">
                <span class="accessibility-text">View Lotus Flower</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Lotus Flower</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24400848 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="3902"
                  href="/prettyuglydesign">
                  <img
                    class="photo lazyload"
                    alt="Ben Didier"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3902/avatars/small/eb51375faf008c355b83c82ec578a2e5.jpg?1672331087"
                    src="" />
                  <span class="display-name">Ben Didier</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24400848 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    162
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    44.6k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24447575"
            data-thumbnail-id="24447575"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Frannie&#39;s Coconut Kefir branding consumer packaged goods cpg design food graphic design healthy illustration jar kefir logo mission packaging retro type typography vector"
                  data-srcset="https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15382243/file/original-8ec030675188f6cdef291209ac8e00d4.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24447575"
                href="/shots/24447575-Frannie-s-Coconut-Kefir">
                <span class="accessibility-text"
                  >View Frannie&#39;s Coconut Kefir</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Frannie&#39;s Coconut Kefir</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24447575 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="2838197"
                  href="/JKDesignCo">
                  <img
                    class="photo lazyload"
                    alt="Jim Kennelly"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/2838197/avatars/small/79dc1f860beb37006574ce2d51eb583f.jpg?1542900471"
                    src="" />
                  <span class="display-name">Jim Kennelly</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24447575 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    19
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    1.4k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24385039"
            data-thumbnail-id="24385039"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Illustration apparel golf illustration pattern puma golf"
                  data-srcset="https://cdn.dribbble.com/userupload/15195238/file/original-1c62389686cef528c0e65b8d6a565b3d.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15195238/file/original-1c62389686cef528c0e65b8d6a565b3d.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15195238/file/original-1c62389686cef528c0e65b8d6a565b3d.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15195238/file/original-1c62389686cef528c0e65b8d6a565b3d.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15195238/file/original-1c62389686cef528c0e65b8d6a565b3d.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15195238/file/original-1c62389686cef528c0e65b8d6a565b3d.jpg?resize=800x600&amp;vertical=center 800w"
                  data-src="https://cdn.dribbble.com/userupload/15195238/file/original-1c62389686cef528c0e65b8d6a565b3d.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24385039"
                href="/shots/24385039-Illustration">
                <span class="accessibility-text">View Illustration</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Illustration</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24385039 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="5276"
                  href="/KendrickKidd">
                  <img
                    class="photo lazyload"
                    alt="Kendrick Kidd"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/5276/avatars/small/dbb8a09fa15c56b2cc0c5632dc37a449.jpg?1534262382"
                    src="" />
                  <span class="display-name">Kendrick Kidd</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24385039 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    237
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    57.7k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24384267"
            data-thumbnail-id="24384267"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Kite character china digital dragonfly fish holiday illustration kites sky summer summertime vector"
                  data-srcset="https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15193270/file/original-23b4f2066a0647a9992d9c2c502897c9.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24384267"
                href="/shots/24384267-Kite">
                <span class="accessibility-text">View Kite</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Kite</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24384267 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1629266"
                  href="/marymaka">
                  <img
                    class="photo lazyload"
                    alt="Mary Maka"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1629266/avatars/small/542236023d877a5b38e351ece1530f1d.jpg?1701344489"
                    src="" />
                  <span class="display-name">Mary Maka</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24384267 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    249
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    72k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24214457"
            data-thumbnail-id="24214457"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble video"
              data-video-teaser-small="https://cdn.dribbble.com/userupload/14701494/file/small-45f5b87203a9c51b13773da76875b734.mp4"
              data-video-teaser-medium="https://cdn.dribbble.com/userupload/14701494/file/large-117f67d027d59382148cbc377a77cd2e.mp4"
              data-video-teaser-large="https://cdn.dribbble.com/userupload/14701494/file/large-117f67d027d59382148cbc377a77cd2e.mp4"
              data-video-teaser-original="https://cdn.dribbble.com/userupload/14701494/file/original-ae0470fc10c6c069e8debe1e502c94d7.mp4">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Happy Walkcycle 2d animation animation character animation character design happy happy character jagthund moustache park road street sun sunny day tree animation trees animation walk walk animation walk cycle walkcycle walking"
                  data-srcset="https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/14701494/file/still-c684f71b0c4e853ca68684af7871a1c6.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras">
                <div
                  class="loading-indicator shot-thumbnail-extras-icon disable-media-icons"></div>

                <a
                  class="animated-target"
                  href="/shots/24214457-Happy-Walkcycle">
                  <span class="accessibility-text">Shot Link</span>
                </a>
              </div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24214457"
                href="/shots/24214457-Happy-Walkcycle">
                <span class="accessibility-text">View Happy Walkcycle</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Happy Walkcycle</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24214457 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1951182"
                  href="/jagthund">
                  <img
                    class="photo lazyload"
                    alt="Jagthund"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/1951182/avatars/small/a58ab228b51a5b44a9ead0d0126afd34.jpg?1573129072"
                    src="" />
                  <span class="display-name">Jagthund</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24214457 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    189
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    66.3k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24431946"
            data-thumbnail-id="24431946"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Flower bee flower growth illustration patswerk pattern poster print riso summer vector vintage"
                  data-srcset="https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15333465/file/original-6411f8ddf9d92861a7b1210fe7b2f5f0.png?crop=0x67-1982x1553&amp;resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24431946"
                href="/shots/24431946-Flower">
                <span class="accessibility-text">View Flower</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Flower</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24431946 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="101577"
                  href="/Patswerk">
                  <img
                    class="photo lazyload"
                    alt="Patswerk"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/101577/avatars/small/016e77676b6d1cfa8bb19feb48c946bf.png?1584368590"
                    src="" />
                  <span class="display-name">Patswerk</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24431946 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    85
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    10k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24374734"
            data-thumbnail-id="24374734"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Create, imagine exist branding brazil character color design fun illustration sao paulo thunder rockets ui"
                  data-srcset="https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15166636/file/original-d420dc6740b85bbd5564fb25e2a5df82.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24374734"
                href="/shots/24374734-Create-imagine-exist">
                <span class="accessibility-text"
                  >View Create, imagine exist</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Create, imagine exist</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24374734 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="339280"
                  href="/thunderockets">
                  <img
                    class="photo lazyload"
                    alt="Thunder Rockets"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/339280/avatars/small/7891ae0ff7ff23a4795e33b3ad2b4a91.png?1637511612"
                    src="" />
                  <span class="display-name">Thunder Rockets</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24374734 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    85
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    21k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24420980"
            data-thumbnail-id="24420980"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Pixel watch case redesign google illustration pixel titanium watch watchface wearable"
                  data-srcset="https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15301656/file/original-ddd23872180ed3ba200dd3d6d3b3ae12.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24420980"
                href="/shots/24420980-Pixel-watch-case-redesign">
                <span class="accessibility-text"
                  >View Pixel watch case redesign</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Pixel watch case redesign</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24420980 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="110792"
                  href="/SLRNCL">
                  <img
                    class="photo lazyload"
                    alt="Nicolas Solerieu"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/110792/avatars/small/fdda67338400982a34cdb8ae8eb448ef.jpg?1664751628"
                    src="" />
                  <span class="display-name">Nicolas Solerieu</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24420980 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    71
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    7.9k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24244791"
            data-thumbnail-id="24244791"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="HHC Living Brand Pattern brand design brand identity branding branding design classic detailed elegant hand drawn identity design illustration illustrator logo logo design luxurious luxury pattern pattern design toile vintage visual identity"
                  data-srcset="https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/14788990/file/original-11f80ded52fd0ad49827b3d1fe913e36.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24244791"
                href="/shots/24244791-HHC-Living-Brand-Pattern">
                <span class="accessibility-text"
                  >View HHC Living Brand Pattern</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">HHC Living Brand Pattern</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24244791 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="3365798"
                  href="/coric_design">
                  <img
                    class="photo lazyload"
                    alt="Coric Design"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3365798/avatars/small/27142d0984a19231593be35a9972bbc4.jpg?1673891024"
                    src="" />
                  <span class="display-name">Coric Design</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24244791 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    146
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    43.9k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24401074"
            data-thumbnail-id="24401074"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Rumble Golf Brand Identity gold branding golf golf ball golf brand golf identity golf logo hand lettering lettering ligature logo logotype rumble rumble golf script type typography wells wells collins wordmark"
                  data-srcset="https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15244022/file/original-73412caacf230200f2fe93230a460aac.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24401074"
                href="/shots/24401074-Rumble-Golf-Brand-Identity">
                <span class="accessibility-text"
                  >View Rumble Golf Brand Identity</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Rumble Golf Brand Identity</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24401074 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="77241"
                  href="/wellscollins">
                  <img
                    class="photo lazyload"
                    alt="Wells Collins"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/77241/avatars/small/e3a0069803b02cfdb3cb9031ecd3b12e.jpg?1599151966"
                    src="" />
                  <span class="display-name">Wells Collins</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24401074 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    349
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    66.9k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24414611"
            data-thumbnail-id="24414611"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Blue Ribbon Beer Branding Design branding design illustration"
                  data-srcset="https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15283049/file/original-ab2fa71f7a1314643a57643e147d6562.png?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24414611"
                href="/shots/24414611-Blue-Ribbon-Beer-Branding-Design">
                <span class="accessibility-text"
                  >View Blue Ribbon Beer Branding Design</span
                >
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Blue Ribbon Beer Branding Design</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24414611 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="1094383"
                  href="/marcato">
                  <img
                    class="photo lazyload"
                    alt="Marcato Studio"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/3020225/avatars/small/dca621eb9a63cba93a93bb0105958185.png?1579079964"
                    src="" />
                  <span class="display-name">Marcato Studio</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-team">Team</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24414611 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    91
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    34k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24432597"
            data-thumbnail-id="24432597"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Post-humanity abstract character city concept design illustration zutto"
                  data-srcset="https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15335495/file/original-def6377680e7a05cbce5920b2755c231.png?crop=43x76-1579x1228&amp;resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24432597"
                href="/shots/24432597-Post-humanity">
                <span class="accessibility-text">View Post-humanity</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Post-humanity</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24432597 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="78464"
                  href="/zuttoworld">
                  <img
                    class="photo lazyload"
                    alt="Alexandra Zutto"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/78464/avatars/small/a9ae6a559ab479d179e8bd22591e4028.jpg?1465908886"
                    src="" />
                  <span class="display-name">Alexandra Zutto</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24432597 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    88
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    16.2k
                  </span>
                </div>
              </div>
            </div>
          </li>

          <li
            id="screenshot-24391255"
            data-thumbnail-id="24391255"
            class="shot-thumbnail js-thumbnail shot-thumbnail-container"
            data-ad-data=""
            data-boost-id=""
            data-is-boost-fallback=""
            data-request-source=""
            data-track-location="Shot"
            data-search-uuid="ad2b8156-d438-4192-a4b6-498b9abb6a2d">
            <div
              class="js-thumbnail-base shot-thumbnail-base disabled-shot-section dribbble-shot dribbble">
              <figure
                class="js-thumbnail-placeholder shot-thumbnail-placeholder">
                <img
                  alt="Creative Works West branding character drawing graphic humour illustration money painter plant speech bubble stars"
                  data-srcset="https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=320x240&amp;vertical=center 320w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=400x300&amp;vertical=center 400w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=450x338&amp;vertical=center 450w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=640x480&amp;vertical=center 640w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=700x525&amp;vertical=center 700w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=800x600&amp;vertical=center 800w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=840x630&amp;vertical=center 840w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=1000x750&amp;vertical=center 1000w, https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=1200x900&amp;vertical=center 1200w"
                  data-src="https://cdn.dribbble.com/userupload/15213807/file/original-de5d698e1e189326674072b36c1bbec4.jpg?resize=400x300&amp;vertical=center"
                  data-sizes="auto"
                  class="lazyload"
                  src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
              </figure>

              <div class="shot-thumbnail-extras"></div>

              <a
                class="shot-thumbnail-link dribbble-link js-shot-link"
                data-turbo="true"
                data-shot-thumbnail-link="24391255"
                href="/shots/24391255-Creative-Works-West">
                <span class="accessibility-text">View Creative Works West</span>
              </a>
              <div class="shot-thumbnail-overlay">
                <div class="shot-thumbnail-overlay-content">
                  <div class="shot-title">Creative Works West</div>

                  <ul class="js-dribbble-shot-actions shot-actions-container">
                    <li data-bucket-container="true" class="shot-action">
                      <a
                        class="bucket-shot btn2 btn2--circle btn2--secondary-alt"
                        title="Save shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="bucket-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M3.33337 5.2C3.33337 4.0799 3.33337 3.51984 3.55136 3.09202C3.74311 2.71569 4.04907 2.40973 4.42539 2.21799C4.85322 2 5.41327 2 6.53337 2H9.46671C10.5868 2 11.1469 2 11.5747 2.21799C11.951 2.40973 12.257 2.71569 12.4487 3.09202C12.6667 3.51984 12.6667 4.0799 12.6667 5.2V14L8.00004 11.3333L3.33337 14V5.2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>
                      </a>
                    </li>

                    <div class="like-action-24391255 shot-action">
                      <a
                        class="btn2 btn2--secondary-alt btn2--circle btn2--secondary-alt tipsy-mobile-disabled like-shot"
                        rel="no-follow"
                        title="Like this shot"
                        data-signup-trigger="true"
                        data-href="/signup/new"
                        data-context="like-shot"
                        href="/signup/new">
                        <svg
                          xmlns="http://www.w3.org/2000/svg"
                          width="16"
                          height="16"
                          viewBox="0 0 16 16"
                          fill="none"
                          role="img"
                          class="icon">
                          <path
                            d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"></path>
                        </svg>

                        <span class="accessibility-text">Like</span>
                      </a>
                    </div>
                  </ul>
                </div>
              </div>
            </div>

            <div class="shot-details-container js-shot-details-container">
              <div class="user-information" data-uuid-passthrough>
                <a
                  class="hoverable url"
                  rel="contact"
                  data-search-profile-clicked="59947"
                  href="/studioMUTI">
                  <img
                    class="photo lazyload"
                    alt="MUTI"
                    width="24"
                    height="24"
                    data-src="https://cdn.dribbble.com/users/59947/avatars/small/5ed2865a861fcd2bc9f9d9aff7600f8b.jpg?1574070463"
                    src="" />
                  <span class="display-name">MUTI</span>
                </a>
                <a class="badge-link" href="/pro">
                  <span class="badge badge-pro">Pro</span>
                </a>
              </div>
              <div class="shot-statistics-container js-shot-statistics">
                <div class="shot-statistic js-shot-likes-container">
                  <div class="like-action-24391255 compact-true shot-action">
                    <a
                      class="btn2--secondary-alt tipsy-mobile-disabled like-shot"
                      rel="no-follow"
                      title="Like this shot"
                      data-signup-trigger="true"
                      data-href="/signup/new"
                      data-context="like-shot"
                      href="/signup/new">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        role="img"
                        class="icon fill-current shot-tools-icon">
                        <path
                          d="M10.7408 2C13.0889 2 14.6667 4.235 14.6667 6.32C14.6667 10.5425 8.11856 14 8.00004 14C7.88152 14 1.33337 10.5425 1.33337 6.32C1.33337 4.235 2.91115 2 5.2593 2C6.60745 2 7.48893 2.6825 8.00004 3.2825C8.51115 2.6825 9.39263 2 10.7408 2Z"
                          stroke="currentColor"
                          stroke-width="1.5"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                      </svg>

                      <span class="accessibility-text">Like</span>
                    </a>
                  </div>

                  <span
                    class="js-shot-likes-count color-deep-blue-sea-light-20 font-weight-500">
                    289
                  </span>
                </div>
                <div class="shot-statistic js-shot-views-container">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="16"
                    height="16"
                    viewBox="0 0 16 16"
                    fill="none"
                    role="img"
                    class="icon fill-current shot-tools-icon">
                    <path
                      d="M8 3C4.36992 3 1.98789 6.21774 1.18763 7.49059C1.09079 7.64462 1.04237 7.72163 1.01527 7.84042C0.99491 7.92964 0.99491 8.07036 1.01527 8.15958C1.04237 8.27837 1.09079 8.35539 1.18763 8.50941C1.98789 9.78226 4.36992 13 8 13C11.6301 13 14.0121 9.78226 14.8124 8.50941L14.8124 8.50939C14.9092 8.35538 14.9576 8.27837 14.9847 8.15958C15.0051 8.07036 15.0051 7.92964 14.9847 7.84042C14.9576 7.72163 14.9092 7.64462 14.8124 7.4906L14.8124 7.49059C14.0121 6.21774 11.6301 3 8 3Z"
                      fill="currentColor"></path>
                    <path
                      d="M8 10C9.10457 10 10 9.10457 10 8C10 6.89543 9.10457 6 8 6C6.89543 6 6 6.89543 6 8C6 9.10457 6.89543 10 8 10Z"
                      fill="white"></path>
                  </svg>

                  <span
                    class="js-shot-views-count color-deep-blue-sea-light-20 font-weight-500">
                    78.3k
                  </span>
                </div>
              </div>
            </div>
          </li>
        </ol>

        <div id="boosted-shots-app"></div>

        <a
          class="home-feed__cta btn2 btn2--secondary btn2--large"
          href="/shots/popular"
          >Browse more inspiration</a
        >
      </div>

      <section class="footer-cta" data-track-location="Lower Pricing Tiers">
        <div class="footer-cta__content home-container">
          <h2 class="footer-cta__heading home-type-heading">
            Find your next designer today
          </h2>

          <div class="footer-cta__copy">
            The world’s leading brands use Dribbble to hire creative talent.
            Browse millions of top-rated portfolios to find your perfect
            creative match.
          </div>

          <div class="footer-cta__actions">
            <a
              class="btn2 btn2--large"
              data-track-cta="Get started"
              href="/signup/new?return_to_after_signup=%2Fget-started%3Fintention%3Dhire%23hiringWorkType"
              >Get started now</a
            >
            <a
              href="/hiring"
              class="btn2 btn2--secondary-alt btn2--large"
              data-track-cta="Learn about hiring"
              >Learn about hiring</a
            >
          </div>

          <div class="footer-cta__copy">
            Are you a designer?
            <a data-track-cta="Join Dribbble" href="/signup/new"
              >Join Dribbble</a
            >
          </div>
        </div>
      </section>
    </main>

    <div
      id="footer"
      class="footer-v2 js-site-footer"
      data-footer-v2
      role="contentinfo">
      <div
        class="footer-v2-marquee"
        data-footer-v2-marquee
        style="--item-count: 8">
        <div class="footer-v2-marquee__track">
          <div class="footer-v2-marquee__grid">
            <a
              href="/shots/popular/branding"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #e6fdc9; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Branding"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15185043/file/original-3c7feee677485a02a8a3b501e6422041.jpg?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Branding</div>
            </a>
            <a
              href="/shots/popular/web-design"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #edf3d8; --stack-color-2: #edddfb">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Web Design"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15363411/file/original-e4f27a7bfd87686223e7fb4c82532996.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Web Design</div>
            </a>
            <a
              href="/shots/popular/illustration"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #e6fbfe; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Illustration"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15316293/file/original-0e92d13c55be4412554176c5ea202458.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Illustration</div>
            </a>
            <a
              href="/shots/popular/mobile"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #e3ebfd; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Mobile"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15351141/file/still-ac8f61798ba08081b5fd007e754bc060.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Mobile</div>
            </a>
            <a
              href="/shots/popular/print"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #e6fbfe; --stack-color-2: #ddfde8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Print"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15162462/file/original-96047224fed22f7d5186faa1c288d423.png?crop=65x275-1558x1395&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Print</div>
            </a>
            <a
              href="/shots/popular/animation"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #f6d9fb; --stack-color-2: #e3ebfd">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Animation"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15357703/file/still-469cd059df9fe1b522b35f02e88e739e.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Animation</div>
            </a>
            <a
              href="/shots/popular/typography"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #ddfde8; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Typography"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/14912170/file/original-b1c51a42f28c7bbc9e0a76841555e0c1.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Typography</div>
            </a>
            <a
              href="/shots/popular/product-design"
              class="footer-v2-marquee-item"
              style="--stack-color-1: #edddfb; --stack-color-2: #ddfde8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Product Design"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15156974/file/original-11870d1037e86271f0f723c56363cdb6.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Product Design</div>
            </a>
            <a
              href="/shots/popular/branding"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #e6fdc9; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Branding"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15185043/file/original-3c7feee677485a02a8a3b501e6422041.jpg?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Branding</div>
            </a>
            <a
              href="/shots/popular/web-design"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #edf3d8; --stack-color-2: #edddfb">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Web Design"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15363411/file/original-e4f27a7bfd87686223e7fb4c82532996.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Web Design</div>
            </a>
            <a
              href="/shots/popular/illustration"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #e6fbfe; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Illustration"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15316293/file/original-0e92d13c55be4412554176c5ea202458.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Illustration</div>
            </a>
            <a
              href="/shots/popular/mobile"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #e3ebfd; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Mobile"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15351141/file/still-ac8f61798ba08081b5fd007e754bc060.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Mobile</div>
            </a>
            <a
              href="/shots/popular/print"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #e6fbfe; --stack-color-2: #ddfde8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Print"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15162462/file/original-96047224fed22f7d5186faa1c288d423.png?crop=65x275-1558x1395&amp;format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Print</div>
            </a>
            <a
              href="/shots/popular/animation"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #f6d9fb; --stack-color-2: #e3ebfd">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Animation"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15357703/file/still-469cd059df9fe1b522b35f02e88e739e.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Animation</div>
            </a>
            <a
              href="/shots/popular/typography"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #ddfde8; --stack-color-2: #edf3d8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Typography"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/14912170/file/original-b1c51a42f28c7bbc9e0a76841555e0c1.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Typography</div>
            </a>
            <a
              href="/shots/popular/product-design"
              class="footer-v2-marquee-item footer-v2-marquee-item--duplicate"
              style="--stack-color-1: #edddfb; --stack-color-2: #ddfde8">
              <div class="footer-v2-marquee-item__stack"></div>
              <div class="footer-v2-marquee-item__media">
                <img
                  alt="Product Design"
                  width="200"
                  height="150"
                  class="lazyload"
                  data-sizes="auto"
                  data-aspectratio="1.3333333333333333"
                  data-src="https://cdn.dribbble.com/userupload/15156974/file/original-11870d1037e86271f0f723c56363cdb6.png?format=webp&amp;resize={width}x{height}&amp;vertical=center" />
              </div>

              <div class="footer-v2-marquee-item__title">Product Design</div>
            </a>
          </div>
        </div>
      </div>

      <div class="footer-v2__container">
        <div class="footer-v2__upper">
          <a class="footer-v2__logo" href="/">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="76"
              height="30"
              viewBox="0 0 210 59"
              fill="none">
              <title>Dribbble: the community for graphic design</title>
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M206.622 31.928C207.065 31.4116 207.85 31.4352 208.253 31.986H208.25L209.784 34.0834C210.075 34.4864 210.073 35.0425 209.769 35.4349C207.106 38.8893 202.44 42.2143 196.81 42.5359C192.366 42.7887 188.701 41.1051 186.706 37.9221C186.311 37.2925 185.44 37.2557 184.997 37.8511C182.63 41.0286 179.766 43.5134 176.782 43.6845C171.467 43.9876 169.966 40.4228 171.28 32.563C171.412 31.7805 170.726 31.1192 169.987 31.3141C168.885 31.6065 167.715 31.7356 166.528 31.633C166.034 31.5907 165.571 31.8912 165.422 32.3811C163.455 38.8418 158.774 44.8518 152.715 45.1997C148.847 45.421 143.069 43.205 143.647 33.9462C143.695 33.1927 143.019 32.5999 142.323 32.8106C141.11 33.1795 139.804 33.3534 138.474 33.2401C137.981 33.1979 137.52 33.4983 137.371 33.9885C135.404 40.449 130.723 46.4592 124.664 46.8068C120.796 47.0282 115.018 44.8124 115.596 35.5536C115.644 34.7998 114.968 34.207 114.272 34.418C113.059 34.7869 111.753 34.9634 110.423 34.8473C109.93 34.8053 109.469 35.1057 109.32 35.5956C107.352 42.0564 102.672 48.0664 96.6132 48.4142C93.8613 48.5723 90.1398 47.4945 88.4308 43.5264C88.1016 42.7599 87.1144 42.6438 86.6257 43.3105C84.2334 46.5751 81.3193 49.152 78.2762 49.3259C75.1571 49.505 73.4509 48.2535 72.7091 46.0216C72.4458 45.2339 71.4609 45.0467 70.9293 45.6712C68.8002 48.1744 66.3749 50.0082 63.9216 50.1479C60.1393 50.3666 57.9619 47.563 57.7823 44.1667C57.5747 40.204 59.2887 35.564 61.2025 30.4999C61.4684 29.7964 60.9873 29.0348 60.2608 29.0032C59.157 28.956 57.8963 28.8399 56.7113 28.6185C56.1771 28.5159 55.6583 28.8479 55.5063 29.3907C53.243 37.4716 49.7771 45.392 46.8529 50.074C46.5263 50.5984 45.8505 50.7381 45.3593 50.377L43.1264 48.7331C42.6682 48.393 42.5441 47.7397 42.8504 47.247C47.0759 40.478 50.8278 29.8807 52.1215 22.0421C52.2025 21.5415 52.61 21.17 53.0986 21.141L56.0683 20.9697C56.7493 20.9302 57.2861 21.5652 57.162 22.2634L57.1493 22.3372C57.0379 22.959 57.4532 23.5439 58.0532 23.6257C60.7164 23.992 64.6963 24.0366 67.3975 23.9313C68.157 23.9023 68.6938 24.6875 68.4178 25.4226C66.2507 31.1876 63.3469 39.1765 63.5139 42.3382C63.5899 43.7662 64.2204 44.5462 65.3291 44.4829C67.4508 44.3619 70.7141 40.0959 73.1876 35.3455C73.2331 35.261 73.2659 35.169 73.2862 35.0741C74.1196 31.3543 75.3565 27.2068 76.6061 23.0163L76.6837 22.7561C76.8128 22.3188 77.1901 22.0131 77.6306 21.9868L81.1876 21.7839C81.9219 21.7417 82.4712 22.4795 82.2485 23.2093C82.0654 23.8112 81.883 24.409 81.7023 25.0014C78.5723 35.2603 75.9438 43.8759 79.4838 43.6742C81.7978 43.5422 85.0764 39.6164 87.8966 34.0279C87.9421 33.9356 87.9751 33.8381 87.9954 33.7355C88.1372 33.0055 88.3092 32.2416 88.5195 31.4432C90.1639 24.8753 92.0286 18.3691 93.8955 11.855C94.4717 9.8446 95.0481 7.83341 95.6182 5.81945C95.7449 5.37417 96.1245 5.06062 96.57 5.03426L100.221 4.82611C100.963 4.78396 101.512 5.52962 101.279 6.26474C99.8208 10.8388 98.2967 15.7106 96.8487 20.4006C96.5448 21.3887 97.603 22.2107 98.4386 21.6416C99.8791 20.6562 101.545 20.0027 103.158 19.9105C107.267 19.676 110.064 23.0565 110.332 28.1496C110.347 28.4184 110.363 28.7082 110.37 29.0032C110.385 29.5673 110.808 30.023 111.348 30.0704C113.282 30.2417 115.259 29.6673 116.786 28.3051C116.943 28.1654 117.049 27.9757 117.102 27.7701C118.616 21.8916 120.287 16.0568 121.959 10.2147C122.532 8.21455 123.105 6.21353 123.672 4.20956C123.798 3.76427 124.178 3.45072 124.624 3.42438L128.274 3.21623C129.016 3.17408 129.566 3.91972 129.333 4.65484C127.874 9.22892 126.35 14.1007 124.902 18.7907C124.598 19.7788 125.657 20.6008 126.492 20.0317C127.933 19.0463 129.599 18.3929 131.211 18.3006C135.32 18.0662 138.117 21.4466 138.386 26.5399C138.401 26.8084 138.416 27.0985 138.424 27.3935C138.436 27.9573 138.862 28.4132 139.401 28.4607C141.335 28.6318 143.312 28.0573 144.839 26.6951C144.996 26.5557 145.102 26.3659 145.156 26.1604C146.67 20.2818 148.34 14.4471 150.013 8.6051C150.586 6.60484 151.158 4.60372 151.725 2.59968C151.852 2.15439 152.232 1.84085 152.677 1.8145L156.328 1.60635C157.07 1.56419 157.619 2.30985 157.386 3.04497C155.928 7.61902 154.404 12.4908 152.956 17.1808C152.652 18.1689 153.71 18.991 154.546 18.4219C155.986 17.4364 157.652 16.783 159.265 16.6908C163.374 16.4563 166.171 19.8367 166.44 24.9299C166.455 25.2013 166.47 25.4885 166.477 25.7835C166.493 26.3447 166.913 26.8032 167.452 26.8507C169.323 27.0166 171.237 26.4844 172.741 25.2171C172.908 25.0774 173.024 24.8798 173.08 24.6637C174.804 18.0187 177.336 9.31324 179.777 0.981894C179.906 0.541877 180.285 0.236236 180.726 0.209888L184.344 0.0017367C185.078 -0.0404207 185.627 0.692063 185.407 1.42191C182.047 12.5778 179.308 22.3372 177.797 28.0944C175.789 35.9039 175.711 38.1567 177.994 38.025C179.911 37.9143 182.493 35.1952 184.928 31.0847C185.025 30.924 185.075 30.7397 185.083 30.5526C185.402 22.324 190.447 14.8385 197.946 14.409C202.969 14.1218 205.721 17.916 205.918 21.6495C206.293 28.7767 199.248 33.3324 192.42 32.9107C191.625 32.8606 191.047 33.7145 191.397 34.4574C192.351 36.4967 194.359 37.6352 197.787 37.4374C201.048 37.2531 204.468 34.439 206.622 31.928ZM93.7548 33.9278C92.1345 40.4228 94.1017 42.9652 96.646 42.8203C100.823 42.5805 104.864 34.9263 104.553 29.019C104.416 26.4396 102.907 25.0958 101.145 25.1961C98.2106 25.3646 95.0512 28.745 93.7548 33.9278ZM121.808 32.3207C120.188 38.8154 122.155 41.3581 124.7 41.2131H124.697C128.874 40.9734 132.917 33.3192 132.606 27.4119C132.472 24.8324 130.96 23.4886 129.198 23.5887C126.264 23.7574 123.105 27.1379 121.808 32.3207ZM149.862 30.7133C148.242 37.2082 150.209 39.7509 152.753 39.606H152.751C156.925 39.3662 160.971 31.712 160.66 25.8047C160.525 23.2251 159.014 21.8814 157.252 21.9815C154.318 22.1501 151.158 25.5307 149.862 30.7133ZM200.584 22.2239C200.559 20.5218 199.513 19.2887 197.817 19.3862H197.815C194.483 19.5785 191.875 23.1856 191.045 27.562C190.913 28.2577 191.422 28.9058 192.103 28.8899C196.407 28.7821 200.721 25.9416 200.584 22.2239ZM44.3525 25.3837C43.9171 12.1962 35.3423 3.49339 22.6712 3.94658C17.2307 4.19426 11.0052 6.25733 6.32164 9.9461C5.88113 10.2939 5.76719 10.9315 6.06593 11.4163L8.05331 14.6519C8.39254 15.2052 9.11407 15.3185 9.60776 14.9075C13.1724 11.9459 18.0383 10.0041 22.7193 9.79855C31.403 9.43757 37.7828 14.9971 38.1551 25.7367C38.6209 38.2417 30.2157 52.5461 16.7091 53.3207C16.2382 53.3471 15.7471 53.3577 15.2559 53.3577C14.5673 53.3577 14.0585 52.6858 14.2306 51.9901C16.8357 41.4744 19.8763 30.1974 22.9776 19.7029C23.1928 18.973 22.6459 18.2458 21.9143 18.288L17.9648 18.5146C17.5218 18.5409 17.142 18.8492 17.0129 19.2918C14.0331 29.6045 11.0508 40.7895 8.36723 51.284C8.21279 51.89 7.59761 52.2379 7.02544 52.0427C5.62543 51.566 4.34693 51.0232 3.2583 50.3881C2.73677 50.0825 2.07601 50.2987 1.80765 50.8571L0.11142 54.4037C-0.139216 54.9281 0.0455967 55.5709 0.539275 55.8527C4.38489 58.0345 10.223 59.2806 16.0914 58.9462C35.4032 57.8393 44.864 40.0015 44.3525 25.3889V25.3837ZM82.3044 9.18082C79.955 9.31518 77.8713 11.9553 78.0183 14.7377C78.1143 16.5715 79.2917 17.7967 81.1195 17.694C83.4689 17.5596 85.6106 14.7798 85.4714 12.1318C85.3754 10.298 84.0005 9.08333 82.3044 9.18082Z"
                fill="currentColor"></path>
            </svg>

            <span class="accessibility-text">Back to home page</span>
          </a>

          <ul class="footer-v2__links">
            <li>
              <a class="footer-v2__link" href="/for-designers">For designers</a>
            </li>
            <li><a class="footer-v2__link" href="/hiring">Hire talent</a></li>
            <li>
              <a class="footer-v2__link" href="/shots/popular">Inspiration</a>
            </li>
            <li>
              <a class="footer-v2__link" href="/advertise">Advertising</a>
            </li>
            <li><a class="footer-v2__link" href="/stories">Blog</a></li>
            <li><a class="footer-v2__link" href="/about">About</a></li>
            <li><a class="footer-v2__link" href="/careers">Careers</a></li>
            <li><a class="footer-v2__link" href="/contact">Support</a></li>
          </ul>
          <div class="footer-v2__social-links">
            <a
              href="http://twitter.com/dribbble"
              class="footer-v2__social-link">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                aria-labelledby="amkbl2wj5w14abk3kyz9mjc83qeej703"
                role="img"
                viewBox="0 0 24 24"
                class="icon">
                <title id="amkbl2wj5w14abk3kyz9mjc83qeej703">
                  Twitter icon
                </title>
                <path
                  d="M23.954 4.569c-.885.389-1.83.654-2.825.775 1.014-.611 1.794-1.574 2.163-2.723-.951.555-2.005.959-3.127 1.184-.896-.959-2.173-1.559-3.591-1.559-2.717 0-4.92 2.203-4.92 4.917 0 .39.045.765.127 1.124C7.691 8.094 4.066 6.13 1.64 3.161c-.427.722-.666 1.561-.666 2.475 0 1.71.87 3.213 2.188 4.096-.807-.026-1.566-.248-2.228-.616v.061c0 2.385 1.693 4.374 3.946 4.827-.413.111-.849.171-1.296.171-.314 0-.615-.03-.916-.086.631 1.953 2.445 3.377 4.604 3.417-1.68 1.319-3.809 2.105-6.102 2.105-.39 0-.779-.023-1.17-.067 2.189 1.394 4.768 2.209 7.557 2.209 9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63.961-.689 1.8-1.56 2.46-2.548l-.047-.02z"></path>
              </svg>

              <span class="accessibility-text">Twitter</span>
            </a>

            <a
              href="http://facebook.com/dribbble"
              class="footer-v2__social-link">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                aria-labelledby="ax25mw5q6m3vf0doqle536hqoy157bf"
                role="img"
                viewBox="0 0 24 24"
                class="icon">
                <title id="ax25mw5q6m3vf0doqle536hqoy157bf">
                  Facebook icon
                </title>
                <path
                  d="M22.676 0H1.324C.593 0 0 .593 0 1.324v21.352C0 23.408.593 24 1.324 24h11.494v-9.294H9.689v-3.621h3.129V8.41c0-3.099 1.894-4.785 4.659-4.785 1.325 0 2.464.097 2.796.141v3.24h-1.921c-1.5 0-1.792.721-1.792 1.771v2.311h3.584l-.465 3.63H16.56V24h6.115c.733 0 1.325-.592 1.325-1.324V1.324C24 .593 23.408 0 22.676 0"></path>
              </svg>

              <span class="accessibility-text">Facebook</span>
            </a>

            <a
              href="http://instagram.com/dribbble"
              class="footer-v2__social-link">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 16 16"
                fill-rule="evenodd"
                clip-rule="evenodd"
                stroke-linejoin="round"
                stroke-miterlimit="1.414"
                role="img"
                class="icon">
                <path
                  d="M8 0C5.827 0 5.555.01 4.702.048 3.85.088 3.27.222 2.76.42c-.526.204-.973.478-1.417.923-.445.444-.72.89-.923 1.417-.198.51-.333 1.09-.372 1.942C.008 5.555 0 5.827 0 8s.01 2.445.048 3.298c.04.852.174 1.433.372 1.942.204.526.478.973.923 1.417.444.445.89.72 1.417.923.51.198 1.09.333 1.942.372.853.04 1.125.048 3.298.048s2.445-.01 3.298-.048c.852-.04 1.433-.174 1.942-.372.526-.204.973-.478 1.417-.923.445-.444.72-.89.923-1.417.198-.51.333-1.09.372-1.942.04-.853.048-1.125.048-3.298s-.01-2.445-.048-3.298c-.04-.852-.174-1.433-.372-1.942-.204-.526-.478-.973-.923-1.417-.444-.445-.89-.72-1.417-.923-.51-.198-1.09-.333-1.942-.372C10.445.008 10.173 0 8 0zm0 1.44c2.136 0 2.39.01 3.233.048.78.036 1.203.166 1.485.276.374.145.64.318.92.598.28.28.453.546.598.92.11.282.24.705.276 1.485.038.844.047 1.097.047 3.233s-.01 2.39-.048 3.233c-.036.78-.166 1.203-.276 1.485-.145.374-.318.64-.598.92-.28.28-.546.453-.92.598-.282.11-.705.24-1.485.276-.844.038-1.097.047-3.233.047s-2.39-.01-3.233-.048c-.78-.036-1.203-.166-1.485-.276-.374-.145-.64-.318-.92-.598-.28-.28-.453-.546-.598-.92-.11-.282-.24-.705-.276-1.485C1.45 10.39 1.44 10.136 1.44 8s.01-2.39.048-3.233c.036-.78.166-1.203.276-1.485.145-.374.318-.64.598-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276C5.61 1.45 5.864 1.44 8 1.44zm0 2.452c-2.27 0-4.108 1.84-4.108 4.108 0 2.27 1.84 4.108 4.108 4.108 2.27 0 4.108-1.84 4.108-4.108 0-2.27-1.84-4.108-4.108-4.108zm0 6.775c-1.473 0-2.667-1.194-2.667-2.667 0-1.473 1.194-2.667 2.667-2.667 1.473 0 2.667 1.194 2.667 2.667 0 1.473-1.194 2.667-2.667 2.667zm5.23-6.937c0 .53-.43.96-.96.96s-.96-.43-.96-.96.43-.96.96-.96.96.43.96.96z"></path>
              </svg>

              <span class="accessibility-text">Instagram</span>
            </a>

            <a
              href="http://www.pinterest.com/dribbble/"
              class="footer-v2__social-link">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                aria-labelledby="ao9z6ar3eezsgnrcbl4n5oap5wo3shrr"
                role="img"
                viewBox="0 0 24 24"
                class="icon">
                <title id="ao9z6ar3eezsgnrcbl4n5oap5wo3shrr">
                  Pinterest icon
                </title>
                <path
                  d="M12.017 0C5.396 0 .029 5.367.029 11.987c0 5.079 3.158 9.417 7.618 11.162-.105-.949-.199-2.403.041-3.439.219-.937 1.406-5.957 1.406-5.957s-.359-.72-.359-1.781c0-1.663.967-2.911 2.168-2.911 1.024 0 1.518.769 1.518 1.688 0 1.029-.653 2.567-.992 3.992-.285 1.193.6 2.165 1.775 2.165 2.128 0 3.768-2.245 3.768-5.487 0-2.861-2.063-4.869-5.008-4.869-3.41 0-5.409 2.562-5.409 5.199 0 1.033.394 2.143.889 2.741.099.12.112.225.085.345-.09.375-.293 1.199-.334 1.363-.053.225-.172.271-.401.165-1.495-.69-2.433-2.878-2.433-4.646 0-3.776 2.748-7.252 7.92-7.252 4.158 0 7.392 2.967 7.392 6.923 0 4.135-2.607 7.462-6.233 7.462-1.214 0-2.354-.629-2.758-1.379l-.749 2.848c-.269 1.045-1.004 2.352-1.498 3.146 1.123.345 2.306.535 3.55.535 6.607 0 11.985-5.365 11.985-11.987C23.97 5.39 18.592.026 11.985.026L12.017 0z"></path>
              </svg>

              <span class="accessibility-text">Pinterest</span>
            </a>
          </div>
        </div>

        <div class="footer-v2__lower">
          <ul class="footer-v2__lower-list">
            <li>&copy; 2024 Dribbble</li>
            <li><a href="/terms">Terms</a></li>
            <li><a href="/privacy">Privacy</a></li>
            <li><a href="/cookie-policy">Cookies</a></li>
          </ul>

          <ul class="footer-v2__lower-list">
            <li><a href="/directories/jobs">Jobs</a></li>
            <li><a href="/directories/designers">Designers</a></li>
            <li><a href="/directories/freelance-designers">Freelancers</a></li>
            <li><a href="/tags">Tags</a></li>
            <li><a href="/places">Places</a></li>
            <li><a href="/resources">Resources</a></li>
          </ul>
        </div>
      </div>
    </div>

    <div id="signup-overlay" class="overlay">
      <div class="lightbox">
        <a href="#" class="close" aria-label="close">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="25"
            height="25"
            viewBox="0 0 25 25"
            fill="none"
            role="img"
            class="icon icon-24 lazyload">
            <rect x="3" y="5" width="18" height="16" fill="white"></rect>
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M12.5051 0.135254C14.9528 0.135152 17.3455 0.860879 19.3807 2.22066C21.416 3.58044 23.0022 5.51321 23.939 7.77453C24.8757 10.0359 25.1209 12.5242 24.6434 14.9248C24.166 17.3255 22.9873 19.5306 21.2566 21.2614C19.5259 22.9922 17.3207 24.1709 14.9201 24.6485C12.5195 25.126 10.0311 24.881 7.76979 23.9443C5.50843 23.0076 3.57561 21.4214 2.21576 19.3862C0.855913 17.3511 0.130107 14.9583 0.130127 12.5107C0.130141 9.22858 1.43392 6.08092 3.75467 3.76009C6.07542 1.43926 9.22304 0.135377 12.5051 0.135254V0.135254ZM7.13525 16.4156C6.9463 16.6101 6.84148 16.8711 6.84346 17.1423C6.84544 17.4135 6.95406 17.6729 7.14583 17.8647C7.3376 18.0564 7.59711 18.1649 7.86827 18.1668C8.13943 18.1687 8.40044 18.0638 8.59488 17.8748L12.4997 13.9699L16.4103 17.8805C16.6047 18.0698 16.8659 18.1749 17.1372 18.1731C17.4085 18.1712 17.6682 18.0626 17.8601 17.8707C18.0519 17.6788 18.1605 17.4191 18.1623 17.1478C18.164 16.8765 18.0589 16.6153 17.8695 16.421L13.9592 12.5106L17.8847 8.58516C18.072 8.39039 18.1754 8.12994 18.1727 7.85976C18.1701 7.58958 18.0616 7.33122 17.8705 7.14017C17.6795 6.94911 17.4211 6.8406 17.1509 6.83794C16.8808 6.83529 16.6203 6.93869 16.4255 7.12594L12.4997 11.051L8.57998 7.13125C8.38644 6.93769 8.12393 6.82894 7.8502 6.82892C7.57647 6.82891 7.31394 6.93763 7.12038 7.13118C6.92681 7.32472 6.81806 7.58724 6.81804 7.86097C6.81803 8.13469 6.92675 8.39722 7.1203 8.59078L11.0402 12.5106L7.13525 16.4156Z"
              fill="#979797"></path>
          </svg>
        </a>
        <div class="display">
          <div class="processing">Loading…</div>
        </div>
      </div>
    </div>
    <div
      class="shot-overlay js-shot-overlay lazyloading-hidden-container"
      tabindex="-1"
      data-include="css:https://cdn.dribbble.com/assets/components/media-overlay-modal-1da48a08b46b96c81a3eeea6d3ccf3198b224f4ef72d96bcc63045a4646e79bd.css">
      <div class="overlay-content js-overlay-content"></div>
      <div class="shot-nav-prev">
        <div class="shot-nav-button-container">
          <a href="#">
            <div class="shot-nav-button">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                enable-background="new 0 0 24 24"
                viewBox="0 0 24 24"
                role="img"
                class="icon fill-current">
                <path
                  d="m13.532 4.585-7.532 7.415 7.532 7.415c.792.779 2.081.779 2.873 0s.792-2.049 0-2.829l-4.659-4.586 4.659-4.587c.384-.378.595-.88.595-1.414s-.211-1.036-.595-1.414c-.792-.78-2.082-.78-2.873 0z"></path>
              </svg>
            </div>
          </a>
          <span>Previous</span>
        </div>
      </div>
      <div class="shot-nav-next">
        <div class="shot-nav-button-container">
          <a href="#">
            <div class="shot-nav-button">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                enable-background="new 0 0 24 24"
                viewBox="0 0 24 24"
                role="img"
                class="icon fill-current">
                <path
                  d="m10.468 19.415 7.532-7.415-7.532-7.415c-.792-.779-2.081-.779-2.873 0s-.792 2.049 0 2.829l4.659 4.586-4.659 4.587c-.384.378-.595.88-.595 1.414s.211 1.036.595 1.414c.792.78 2.082.78 2.873 0z"></path>
              </svg>
            </div>
          </a>
          <span>Next</span>
        </div>
      </div>
      <a href="#" class="js-close-overlay close-overlay" aria-label="close">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 26 26"
          fill="none"
          role="img"
          class="icon fill-current">
          <path
            d="M8.28596 6.51819C7.7978 6.03003 7.00634 6.03003 6.51819 6.51819C6.03003 7.00634 6.03003 7.7978 6.51819 8.28596L11.2322 13L6.51819 17.714C6.03003 18.2022 6.03003 18.9937 6.51819 19.4818C7.00634 19.97 7.7978 19.97 8.28596 19.4818L13 14.7678L17.714 19.4818C18.2022 19.97 18.9937 19.97 19.4818 19.4818C19.97 18.9937 19.97 18.2022 19.4818 17.714L14.7678 13L19.4818 8.28596C19.97 7.7978 19.97 7.00634 19.4818 6.51819C18.9937 6.03003 18.2022 6.03003 17.714 6.51819L13 11.2322L8.28596 6.51819Z"
            fill="currentColor"></path>
        </svg>
      </a>
    </div>

    <div id="shot-modals-app"></div>
    <div id="good-modals-app"></div>
    </body>
    <div id="site-notifications"></div>
    </html>


    

### OUTPUT:
![](https://github.com/AKASHBKUMAR/css-advanced-project/blob/main/output.jpeg?raw=true)
### RESULT:
    Thus, the task has been completed successfully.
