<script>
  export let title = "Verify Me";
  export let description =
    "Verification without a disposable income.";
  export let url = "https://verifyme.fun";
  export let slug =  "/assets/sharecard.jpg"
</script>

<svelte:head>
  <title>{title}</title>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <meta name="description" content={description} />
  <meta name="author" content="Verify Me" />
  <meta name="news_keywords" content="" />

  <meta property="og:title" content={title} />
  <meta property="og:site_name" content="verifyme" />
  <meta property="og:url" content={url} />
  <meta property="og:description" content={description} />
  <meta property="og:type" content="article" />
  <meta property="og:locale" content="en_US" />

  <meta property="og:image" content="https://verifyme.fun/{slug}" />
  <meta property="og:image:type" content="image/jpeg" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="600" />

  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:site" content="https://verifyme.fun" />
  <meta name="twitter:creator" content="@verifyme" />
  <meta name="twitter:title" content={title} />
  <meta name="twitter:description" content={description} />
  <meta name="twitter:image:src" content="https://verifyme.fun/{slug}" />

  <meta name="robots" content="max-image-preview:large" />

  <link rel="canonical" href="{url}/" />
  <!-- <link rel="apple-touch-icon" sizes="180x180" href="/common/assets/resources/favicon/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/common/assets/resources/favicon/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/common/assets/resources/favicon/favicon-16x16.png"> -->
  <!-- <link rel="manifest" href="/common/assets/resources/favicon/site.webmanifest"> -->
</svelte:head>
