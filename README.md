
<link rel="stylesheet" href="/2023/app/css/program-page.css" />
<link rel="stylesheet" href="/2023/app/css/sessionmacros.css" />

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    
    
    <link rel="icon" type="image/png" href="/2023/app/images/favicon-16x16.png" sizes="16x16">
    <link rel="icon" type="image/png" href="/2023/app/images/favicon-32x32.png" sizes="32x32">
    <link rel="icon" type="image/png" href="/2023/app/favicon-96x96.png" sizes="96x96">
    <link rel="icon" type="image/png" href="/2023/app/images/favicon-android-chrome-192x192.png" sizes="192x192">
    <link rel="icon" type="image/png" href="/2023/app/images/favicon-android-chrome-512x512.png" sizes="512x512">
    <link rel="icon" type="image/png" href="/2023/app/images/favicon-apple-touch-icon-180x180.png" sizes="180x180">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="description"
      content="Tune in to watch the latest news and innovations from Google. Join I/O for livestreamed keynotes and helpful product updates on demand.
"
    />
    <title>Google I/O 2023</title>
    <meta property="og:title" content="Google I/O 2023" />
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://io.google/" />
    <meta property="og:image" content="https://io.google/2023/app/images/og-image.jpg" />
    <meta property="og:description" content="Tune in to watch the latest news and innovations from Google. Join I/O for livestreamed keynotes and helpful product updates on demand.
" />
    <style>
      /* Set sans-serif defaults */
      body,
      html {
        background: white;
        color: #444;
        height: 100%;
        margin: 0;
        padding: 0;
        width: 100%;
      }
      body,
      html,
      h1, h2, h3, h4, h5, h6,
      p, div {
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        font-family: 'Google Sans', Sans-Serif;
      }
      * {
        box-sizing: border-box;
      }
    </style>
    <link
      rel="preconnect"
      href="https://fonts.gstatic.com"
      crossorigin />
    <link rel="preconnect" href="https://storage.googleapis.com"/>
    <link rel="preconnect" href="https://apis.google.com"/>
    <link rel="preload"
      as="style"
      href="https://fonts.googleapis.com/icon?family=Google+Sans:400,500%7CGoogle+Sans+Display:400%7CGoogle+Sans+Text:400|Roboto:400,500|Roboto+Mono:400&display=swap" />
    <link rel="stylesheet"
      href="https://fonts.googleapis.com/icon?family=Google+Sans:400,500%7CGoogle+Sans+Display:400%7CGoogle+Sans+Text:400|Roboto:400,500|Roboto+Mono:400&display=swap"
      media="print" onload="this.media='all'" />
    <link
      rel="stylesheet"
      href="/2023/app/iofe_tailwind.595ad1b1df43a40fa42f1aa19b303aff.css"
    />
    <link
      href="/2023/app/iofe_bundle.23a1a8fbb44df5918d5f.css"
      rel="stylesheet"
      media="only x"
      onload="this.media='all'"
    />
    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
      new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
      j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
      'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
      })(window,document,'script','dataLayer','GTM-MNH554N');</script>
      <!-- End Google Tag Manager -->
  </head>
<body data-phase="phase4-1-post-event" data-prefix="2023">
  <script>
    (function () {
      const mode = localStorage.getItem('gio::theme');
      const systemSetToDarkMode = window.matchMedia('(prefers-color-scheme: dark)').matches === true;
      if (mode === "dark") {
        document.body.classList.add('dark');
      } else if(!mode && systemSetToDarkMode) {
        document.body.classList.add('dark');
        localStorage.setItem('gio::theme', 'dark');
      }
      window.onload = () => {
        const ctas = document.querySelectorAll('[data-analytics-event]');
        ctas.forEach((cta) => {
          cta.addEventListener('click', (event) => {
            trackEvent(cta.dataset.analyticsEvent, cta.dataset.analyticsEventData);
          })
        });
      }
    })();

    const trackFilterCategory = (filterType, event) => {
      if (window.filtersLoaded) {
        // this is getting the current state, so true means it is closing, false means it is opening
        const isOpen = event.currentTarget.getAttribute('aria-expanded') === 'true';
        trackEvent(isOpen ? 'filter_type_close' : 'filter_type_open', {filterType});
      }
    }

    const trackFilter = (event) => {
      if (window.filtersLoaded) {
        trackEvent(
          event.target.checked ? 'filter_select' : 'filter_deselect',
          {
            'filterType': event.target.dataset.classification,
            'filterItem': event.target.dataset.analyticsFilter
          }
        )
      }
    }

    const trackEvent = (eventName, eventData) => {
      if(typeof eventData === 'string') {
        eventData = JSON.parse(eventData);
      }
      const trackingData = {
          event: eventName,
          eventParams: eventData
        }
      if (window && window.dataLayer) {
        window.dataLayer.push(trackingData, {eventParams: undefined});
      }
    }
  </script>
  
  <div id="modal-root"></div>
  <div id="preact_root"></div>
  <header
  id="main-header"
  data-show-map="True"
  class="bg-white dark:bg-grey-900 border-black border-b-2 dark:border-white text-md:border-b-0 lg:bg-white"
>
  
    <div class="h-my-io h-inherit" data-myio="True" data-resources="True" data-allbadges="True">
	<div class="flex justify-end">
		<div id="my-io-drawer" class="my-io-drawer" aria-labelledby="myio-drawer-btn" aria-orientation="vertical" role="dialog">
			<div data-focus-guard tabIndex="0" style="width: 1px; height: 0px; padding: 0px; overflow: hidden; position: fixed; top: 1px; left: 1px;"></div>

			<div class="focus-lock flex flex-col h-inherit">
				<div class="flex w-full justify-between p-1 border-b-2 border-grey-900 dark:border-grey-200 items-center py-2">
					<div class="flex w-2/5 justify-around items-center">
						<button id="myio-profile-pic" class="block w-[32px] h-[32px]" aria-label>
							<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAYAAABS3GwHAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAIZSURBVHgB7dMBDcAwDMCw/Tp/VOXVj0dsKRDyzMweaNr3QJgBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYA0A5BmANIMQJoBSDMAaQYgzQCkGYC077YHmvYHLiMHyvgUKfUAAAAASUVORK5CYII=" class="rounded-full" width="32" height="32" aria-hidden="true" />
						</button>
						<div id="myio-drawer-btn" class="flex min-w-[4rem] items-center justify-center myio-btn !no-underline !cursor-default font-medium dark:text-grey-100 cta-link-btn !text-grey-900 dark:!text-grey-100 "></div>
						<a href="https://developers.google.com/profile/u/me/settings" target="_blank" class="flex items-center p-3" rel="noreferrer">
							<img class="dark:hidden hcm-hidden" src="/2023/app/images/myio-settings.svg" role="img" aria-hidden="true" />
							<img class="hidden dark:block hcm-block" src="/2023/app/images/myio-settings-dark.svg" role="img" aria-hidden="true" />
						</a>
					</div>
					<button class="p-3">
						<img class="dark:hidden hcm-dark-hidden" src="/2023/app/images/myio-close-icon.svg" role="img" aria-hidden="true" />
						<img class="hidden dark:block hcm-block" src="/2023/app/images/myio-close-icon-dark.svg" role="img" aria-hidden="true" />
					</button>
				</div>
				<div class="p-2 overflow-auto">
					<div class="h-max">
						<div class="p-4 ">
							<p class="sm:s-p1 text-grey-900 dark:text-grey-200">
								Create a developer profile to earn badges, save sessions, and get recommended content.
							</p>
							<button class="mt-5 sm:s-button-default text-blue-600 dark:text-blue-dark font-medium link-blue">
								Get started
							</button>
						</div>
						<div class="mb-2">
							<div class="flex flex-col border-2 border-grey-900 dark:border-grey-200 rounded-lg h-full overflow-hidden">
								<div class="bg-blue min-h-24 flex flex-col px-4 py-5 border-b-2 border-black dark:border-grey-200">
									<h3 class="sm:l-h6 md:s-h4 font-medium text-grey-900 mb-1">Saved sessions</h3>
									<span class="hidden underline-link">
										<p>Your saved sessions are automatically saved in your <a href="https://developers.google.com/profile/u/me" target="_blank">developer profile</a></p>
									</span>
								</div>
								<div class="flex flex-col p-4 justify-center h-full items-center ">
									<img class="mx-auto my-4" src="/2023/app/images/myIOSaved.svg" role="img" aria-hidden="true" loading="lazy" />
									<p class=" text-center text-grey-900 dark:text-grey-200">
										Keep track of the sessions you're interested when you save them to My I/O.
									</p>
								</div>
								<div class="flex flex-col overflow-auto max-h-112 myio-scrollbar hidden ">
									<div class>
										<img class="mx-auto my-4" src="/2023/app/images/myio-loading.svg" role="img" aria-hidden="true" loading="lazy" />
									</div>
									<div class="hidden"></div>
									<button class="mt-5 sm:s-button-default text-blue-600 dark:text-blue-dark font-medium link-blue self-center hidden ">Load More</button>
								</div>
							</div>
						</div>
						<div class="mb-2">
							<div class="flex flex-col border-2 border-grey-900 dark:border-grey-200 rounded-lg h-full overflow-hidden">
								<div class="bg-red min-h-24 flex flex-col px-4 py-5 border-b-2 border-black dark:border-grey-200">
									<span class="sm:l-h6 md:s-h4 font-medium text-grey-900 mb-1 ">
										Recommended for you
									</span>
									<span class="hidden underline-link">
										<p>Content is based on the interests you selected in your Your saved sessions are automatically saved in your <a href="https://developers.google.com/profile/u/me" target="_blank">developer profile</a></p>
									</span>
								</div>
								<div class="flex flex-col p-4 justify-center h-full items-center ">
									<img class="mx-auto my-4" src="/2023/app/images/myIORecommended.svg" role="img" aria-hidden="true" loading="lazy" />
									<p class="text-center text-grey-900 dark:text-grey-200">
										Add interests in your developer profile to get content recommendations.
									</p>
								</div>
								<div class="flex flex-col overflow-auto max-h-112 myio-scrollbar  hidden">
									<div class>
										<img class="mx-auto my-4" src="/2023/app/images/myio-loading.svg" role="img" aria-hidden="true" loading="lazy" />
									</div>
									<button class="mt-5 sm:s-button-default text-blue-600 dark:text-blue-dark font-medium link-blue self-center hidden ">Load More</button>
								</div>
							</div>
						</div>
						<div class="mb-2 hidden">
							<div class="flex flex-col border-2 border-grey-900 dark:border-grey-200 rounded-lg h-full overflow-hidden ">
								<div class="bg-yellow min-h-24 flex flex-col px-4 py-5 border-b-2 border-black dark:border-grey-200">
									<h3 class="sm:l-h6 md:s-h4 font-medium text-grey-900 mb-1">Saved resources</h3>
									<span class="hidden underline-link">
										<p>Your saved resources are automatically saved in your <a href="https://developers.google.com/profile/u/me" target="_blank">developer profile</a></p>
									</span>
								</div>
								<div class="flex flex-col p-4 justify-center h-full items-center ">
									<img class="mx-auto my-4" src="/2023/app/images/myIOSaved.svg" role="img" aria-hidden="true" />
									<p class=" text-center text-grey-900 dark:text-grey-200">
										Keep track of the resources you're interested in by saving them to My I/O.
									</p>
								</div>
								<div class="flex flex-col overflow-auto max-h-112 myio-scrollbar hidden">
									<div class>
										<img class="mx-auto my-4" src="/2023/app/images/myio-loading.svg" role="img" aria-hidden="true" />
									</div>
									<button class="mt-5 sm:s-button-default text-blue-600 dark:text-blue-dark font-medium link-blue self-center hidden ">Load More</button>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div data-focus-guard tabIndex="0" style="width: 1px; height: 0px; padding: 0px; overflow: hidden; position: fixed; top: 1px; left: 1px;"></div>
		</div>
		<div class="my-io-drawer-mask hidden"></div>
	</div>
</div>
  
  
  <nav
    id="top-nav"
    class="mx-auto relative header-nav py-3 md:pr-8 flex items-center border-none"
    aria-label="Top"
  >
    
    <div class="block text-md:hidden">
  <div class="flex">
    <button id="hamburger" class="mobileHamburger" tab-index="0" aria-label="Toggle Navigation Bar" aria-controls="drawer-nav">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <rect width="24" height="24" fill="white" fill-opacity="0.01"/>
        <path id="hamburger-path" fill-rule="evenodd" clip-rule="evenodd" d="M3 18H21V16H3V18ZM3 13H21V11H3V13ZM3 6V8H21V6H3Z" fill="#202124" class="fill-grey-900 dark:fill-grey-200"/>
        <mask id="mask0_3949_5619" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="3" y="6" width="18" height="12">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M3 18H21V16H3V18ZM3 13H21V11H3V13ZM3 6V8H21V6H3Z" fill="white"/>
        </mask>
        <g mask="url(#mask0_3949_5619)">
        </g>
      </svg>
    </button>
  </div>
  <div id="drawer-nav" aria-modal="true" aria-hidden="true" class="drawer-nav">
    <div id="drawer-nav-a" class="flex justify-between">
      <a href="/2023/" aria-label="Google I/O home page" class="focus-trapped ml-5">
        <img
          id="normal-logo"
          src="/2023/app/images/Logo.svg"
          class="block dark:hidden logo"
          width="129" height="28"
          role="presentation"
          aria-hidden="true"
          alt=""
        />
        <img
          id="dark-logo"
          src="/2023/app/images/Logo-dark.svg"
          class="hidden dark:block dark-logo"
          width="129" height="28"
          role="presentation"
          aria-hidden="true"
          alt=""
        />
        <img
          id="onsite-logo"
          src="/2023/app/images/Logo-Onsite.svg"
          class="hidden onsite-logo"
          width="129" height="28"
          role="presentation"
          aria-hidden="true"
          alt=""
        />
      </a>
      <button
        id="close-drawer-btn"
        type="button"
        class="ml-auto z-50 p-3 focus-trapped"
        aria-label="Exit"
      >
        <svg
          class="fill-current text-grey-900 w-6 h-6 dark:text-grey-200"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 18 18"
        >
          <path d="M14.53 4.53l-1.06-1.06L9 7.94 4.53 3.47 3.47 4.53 7.94 9l-4.47 4.47 1.06 1.06L9 10.06l4.47 4.47 1.06-1.06L10.06 9z" />
        </svg>
      </button>
    </div>
    
      <div class="h-onsite-mobile-header w-full md:hidden" data-travel="True" data-schedule="True"><div class="font-medium sm:l-cta2 flex flex-col py-6 bg-yellow dark:bg-yellow-dark
        border-grey-900 border-t-2 border-b-2 dark:border-grey-200 hidden"><button aria-controls="onsite-mobile-header" aria-expanded="false" class="flex justify-between w-full focus-trapped"><span class="ml-5 font-medium">Shoreline </span><svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg" class="rotate-0 transform mr-7"><mask id="mask0_2605_269227" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="2" y="5" width="12" height="7"><path d="M3.60602 5.06006L2.66602 6.00006L7.99935 11.3334L13.3327 6.00006L12.3927 5.06006L7.99935 9.44672" fill="white"></path></mask><g mask="url(#mask0_2605_269227)"><rect width="16" height="16" fill="#202124"></rect></g></svg></button><div id="onsite-mobile-header" class="hidden"><div class="flex flex-col mt-5"><a href="/2023/inpersonfaq/" data-category="mobile-nav" data-action="Shoreline" data-label="Frequently Asked Questions" id="faqonsitelink" class="onsite-mobile-links focus-trapped"><span>Shoreline FAQ</span></a><a href="/2023/health-safety/" data-category="mobile-nav" data-action="Shoreline" data-label="Health and Safety" id="healthsafetylink" class="onsite-mobile-links focus-trapped"><span>Health and Safety</span></a><a href="/2023/travel/" data-category="mobile-nav" data-action="Shoreline" data-label="Travel &amp; Accommodations" id="travellink" class="onsite-mobile-links focus-trapped hidden"><span>Transportation and Logistics</span></a><a href="/2023/schedule/" data-category="mobile-nav" data-action="Shoreline" data-label="Schedule" id="schedule" class="onsite-mobile-links focus-trapped hidden"><span class="hidden">Schedule and Map</span><span class>[EN-ONLY KEY MISSING/nt_schedule_pagetitle_phase3]</span></a></div></div></div></div>
    
    
      <div class="flex justify-between items-center pr-2">
        <div class="flex justify-between items-center ml-5 mt-4 pr-2">
          <div class="nav-links inline sm:l-cta2 lg:s-button-default">
            <div class="inline-block relative">
              <a href="/2023/watch/"
                class="focus-trapped"
                langKey="global_watch"
                data-category="main-nav"
                data-action="Products"
                data-label="na"
              >
                Watch
              </a>
            </div>
          </div>
        </div>
      </div>
    
    
    <div class="flex justify-between items-center ml-5 mt-7 pr-2">
      <div class="nav-links inline sm:l-cta2 lg:s-button-default">
        <div class="inline-block relative">
          <a href="/2023/learn/"
            class="focus-trapped"
            langKey="global_learn"
            data-category="main-nav"
            data-action="Learn"
            data-label="na"
          >
            Learn
          </a>
        </div>
      </div>
    </div>
    
    
    
      
      <div class="flex justify-between items-center ml-5 mt-7 pr-2">
        <div class="nav-links inline sm:l-cta2 lg:s-button-default">
          <div class="inline-block relative">
            <a
              href="/2023/community/"
              target="_self"
              aria-label="Join a developer community group near you for networking, events, collaboration, and more."
              class="focus-trapped"
              langKey="global_community"
              data-category="main-nav"
              data-action="Community"
              data-label="na"
            >
            Community
            </a>
          </div>
        </div>
      </div>
    
    
    
      <div class="flex justify-between items-center ml-5 mt-7 pr-2">
        <div class="nav-links inline sm:l-cta2 lg:s-button-default">
          <div class="inline-block relative">
            <a href="/2023/about/"
              class="focus-trapped"
              langKey="global_about"
              data-category="main-nav"
              data-action="About"
              data-label="na"
            >
              About
            </a>
          </div>
        </div>
      </div>
    
    <div class="flex ml:hidden flex-col h-full justify-end m-5">
      <div class="h-choose-language" data-in-footer="">
	<select name="language-select" role="listbox" alt class="font-medium language-select focus-trapped bg-white dark:bg-grey-900 text-grey-900 dark:text-white w-full border-none pl-0 ml:w-32 ml:pl-4 sm:s-cta2 md:s-cta1">
		<option selected value="en"></option>
		<option value="es"></option>
		<option value="pt"></option>
		<option value="fr"></option>
		<option value="id"></option>
		<option value="ko"></option>
		<option value="zh"></option>
		<option value="ja"></option>
	</select>
	<div style="z-index: 10;" class="absolute  invisible">
		<div class="bg-white dark:bg-grey-900 dark:text-grey-200 border-2 border-grey-900 dark:border-grey-200 text-grey-900 sm:l-cta2 font-medium p-2 pr-6 w-full">
			<span></span>
			<button type="button" class="absolute top-0 bottom-0" aria-label="Close">
				<svg class="fill-current dark:fill-white text-grey-900 w-6 h-6 forced-white-color" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 18">
					<path d="m14.53 4.53-1.06-1.06L9 7.94 4.53 3.47 3.47 4.53 7.94 9l-4.47 4.47 1.06 1.06L9 10.06l4.47 4.47 1.06-1.06L10.06 9z"></path>
				</svg>
			</button>
		</div>
		<svg width="32" height="20" viewBox="-2 -2 37 28" fill="none" xmlns="http://www.w3.org/2000/svg" style="bottom: -18px; transform: scale(1, -1); right: 80px;" aria-hidden="true" class="absolute block dark:hidden hcm-hidden">
			<g id="Polygon 1">
				<path d="M0.138981 4.44226C0.0834319 1.0678 3.97439 -0.854559 6.62079 1.23988L35.9246 24.4317C37.4112 25.6083 36.5792 28 34.6834 28L2.49412 28C1.40238 28 0.512363 27.1245 0.494394 26.0329L0.138981 4.44226Z" fill="currentColor" stroke="#202124" stroke-width="2.5" mask="url(#path-1-inside-1_0_1)" class="arrow-white"></path>
			</g>
		</svg>
		<svg width="32" height="20" viewBox="-2 -2 37 28" fill="none" xmlns="http://www.w3.org/2000/svg" style="bottom: -18px; transform: scale(1, -1); right: 80px;" aria-hidden="true" class="absolute hidden dark:block hcm-block">
			<g id="Polygon 1">
				<path d="M0.138981 4.44226C0.0834319 1.0678 3.97439 -0.854559 6.62079 1.23988L35.9246 24.4317C37.4112 25.6083 36.5792 28 34.6834 28L2.49412 28C1.40238 28 0.512363 27.1245 0.494394 26.0329L0.138981 4.44226Z" fill="currentColor" stroke="#E8EAED" stroke-width="2.5" mask="url(#path-1-inside-1_0_1)" class="arrow-white"></path>
			</g>
		</svg>
	</div>
</div>
    </div>
  </div>
  <div id="nav-mask" class="drawer-mask hidden"></div>
</div>

<script defer>
  document.addEventListener("DOMContentLoaded", function () {
    // main controls.
    const drawer = document.getElementById("drawer-nav");
    const mask = document.getElementById("nav-mask");
    const hamburger = document.getElementById("hamburger");
    const closeBtn = document.getElementById("close-drawer-btn");
    // extras for aria hiding.
    const siteLogo = document.getElementById('site-logo');
    const desktopNavLinks = document.getElementById('desktop-nav-links');
    const headerActions = document.getElementById('header-actions');
    const content = document.getElementById('content');
    const footer = document.getElementById('footer');

    // set hamburger button initially.
    toggleAriaExpandedAttribute(false);

    hamburger.addEventListener('click', handleNavToggle);
    mask.addEventListener("click", handleNavToggle);
    closeBtn.addEventListener("click", () => {
      handleNavToggle(true);
    });

    function toggleAriaExpandedAttribute(boolean) {
      hamburger.setAttribute("aria-expanded", boolean);
    }

    function toggleAriaHidden(boolean) {
      drawer.setAttribute("aria-hidden", !boolean);
      desktopNavLinks.setAttribute("aria-hidden", boolean);
      headerActions.setAttribute('aria-hidden', boolean);
      content.setAttribute('aria-hidden', boolean);
      footer.setAttribute('aria-hidden', boolean);
      siteLogo.setAttribute('aria-hidden', boolean);
    }

    function handleNavToggle(forceHide = false) {
      const trapFocusHandler = createTrapFocusHandler(drawer);
      function hide () {
        document.body.style.position = '';
        mask.classList.add("hidden");
        toggleAriaExpandedAttribute(false);
        toggleAriaHidden(false);

        // add focus trap
        document.removeEventListener('keydown', trapFocusHandler);
        return drawer.classList.remove("show");
      }
      function show () {
        document.body.style.position = 'fixed';
        mask.classList.remove("hidden");
        toggleAriaExpandedAttribute(true);
        toggleAriaHidden(true);

        // add focus trap
        document.addEventListener('keydown', trapFocusHandler);
        return drawer.classList.add("show");
      }
      if (forceHide && typeof forceHide === 'boolean') {
        hide();
      } else if (!drawer.classList.contains("show")) {
        show();
      } else {
        hide();
      }
    }
    const getFirstAndLastFocusableElements = el => {
    if (!el) return [];
    const focusableContent = el.querySelectorAll('.focus-trapped:not(.hidden)');

    if (focusableContent.length === 0) {
      return [];
    }
    return [focusableContent[0], focusableContent[focusableContent.length - 1]];
  };

  const createTrapFocusHandler = el => {
    const [firstFocusableElement, lastFocusableElement] =
      getFirstAndLastFocusableElements(el);

    const tabHandler = e => {
      let isTabPressed = e.key === 'Tab' || e.keyCode === 9;

      if (!isTabPressed) {
        return;
      }

      if (e.shiftKey) {
        if (
          lastFocusableElement &&
          firstFocusableElement &&
          document.activeElement === firstFocusableElement
        ) {
          lastFocusableElement.focus();
          e.preventDefault();
        }
      } else {
        if (
          lastFocusableElement &&
          firstFocusableElement &&
          document.activeElement === lastFocusableElement
        ) {
          firstFocusableElement.focus();
          e.preventDefault();
        }
      }
    };
    requestAnimationFrame(() => {
      firstFocusableElement && firstFocusableElement.focus();
    });

    return tabHandler;
  };
  });
</script>

    
    

<a
  id="site-logo"
  href="/2023/"
  class="mr-[1rem] text-md:ml-3"
  data-category="main-nav"
  data-action="Home"
  data-label="na"
  aria-label="Google I/O home page"
>
  
  <svg
    id="medium-main-logo"
    class="block dark:hidden logo"
    aria-hidden="true"
    alt=""
    role="presentation"
    width="154"
    height="64"
    viewBox="0 0 154 64"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g clip-path="url(#clip0_3949_6913)">
    <path d="M20 30.7235C20 25.0386 24.768 20.4086 30.4633 20.4086C31.7722 20.3867 33.0723 20.6268 34.2871 21.1148C35.5018 21.6028 36.6067 22.3288 37.5367 23.2502L35.5387 25.2386C34.1782 23.9273 32.3554 23.2055 30.4659 23.2301C26.318 23.2301 23.0756 26.5703 23.0756 30.727C23.0756 34.8836 26.3128 38.2221 30.4659 38.2221C33.1564 38.2221 34.689 37.141 35.6705 36.1586C36.4757 35.3526 37.0023 34.1929 37.204 32.621H30.4633V29.7917H39.9416C40.0491 30.3752 40.0997 30.9677 40.0927 31.5609C40.0927 33.6733 39.5155 36.2887 37.6537 38.1514C35.8391 40.0297 33.525 41.0261 30.4633 41.0261C24.768 41.0261 20 36.4083 20 30.7217" fill="#202124"/>
    <path d="M47.7491 38.4186C45.7406 38.4186 44.0046 36.7594 44.0046 34.3937C44.0046 32.0281 45.738 30.3698 47.7491 30.3698C49.7602 30.3698 51.491 32.0045 51.491 34.3972C51.491 36.79 49.7576 38.4203 47.7491 38.4203V38.4186ZM47.7491 27.7561C44.0814 27.7561 41.0879 30.5506 41.0879 34.3929C41.0879 38.2352 44.0788 41.0252 47.7491 41.0252C51.4194 41.0252 54.4111 38.2072 54.4111 34.3885C54.4111 30.5698 51.4167 27.7544 47.7491 27.7544V27.7561Z" fill="#202124"/>
    <path d="M62.2793 38.4186C60.2708 38.4186 58.5339 36.7594 58.5339 34.3937C58.5339 32.0281 60.2681 30.3698 62.2793 30.3698C64.2904 30.3698 66.0246 32.0045 66.0246 34.3972C66.0246 36.79 64.2904 38.4238 62.2793 38.4238V38.4186ZM62.2793 27.7596C58.6116 27.7596 55.6172 30.554 55.6172 34.3964C55.6172 38.2387 58.609 41.0287 62.2793 41.0287C65.9495 41.0287 68.9413 38.2107 68.9413 34.392C68.9413 30.5733 65.9495 27.7544 62.2793 27.7544V27.7596Z" fill="#202124"/>
    <path d="M87.8112 21.1143H84.8945V40.6332H87.8112V21.1143Z" fill="#202124"/>
    <path d="M87.8112 21.1143H84.8945V40.6332H87.8112V21.1143Z" fill="#202124"/>
    <path d="M95.5801 30.3207C96.7372 30.3207 97.717 30.8979 98.0427 31.7292L92.1107 34.1935C92.0339 31.627 94.0965 30.3207 95.5793 30.3207H95.5801ZM95.8055 38.4201C94.3209 38.4201 93.266 37.7407 92.5884 36.4116L101.464 32.7378L101.165 31.9894C100.612 30.5049 98.9291 27.7646 95.4841 27.7646C92.0391 27.7646 89.2246 30.4569 89.2246 34.4014C89.2246 38.124 92.0409 41.0381 95.8116 41.0381C96.9056 41.0437 97.9838 40.7774 98.9493 40.2629C99.9148 39.7484 100.737 39.002 101.343 38.0909L99.0802 36.5819C98.3196 37.6857 97.2891 38.4201 95.8063 38.4201H95.8055Z" fill="#202124"/>
    <path d="M76.7785 38.4205C74.7701 38.4205 73.0829 36.7351 73.0829 34.4219C73.0829 32.1086 74.7674 30.3717 76.7785 30.3717C78.7896 30.3717 80.3135 32.0815 80.3135 34.4219C80.3135 36.7622 78.7608 38.4205 76.7751 38.4205H76.7785ZM80.1144 28.1571V29.2365H80.0139C79.3599 28.4506 78.1033 27.752 76.5209 27.752C73.2026 27.752 70.1602 30.6704 70.1602 34.4184C70.1602 38.1664 73.2017 41.0263 76.5209 41.0263C78.1041 41.0263 79.3608 40.3277 80.0139 39.5173H80.1144V40.4726C80.1144 43.0129 78.7573 44.3708 76.5786 44.3708C74.7936 44.3708 73.6881 43.088 73.2401 42.0131L70.7007 43.0706C71.1784 44.2388 71.9949 45.2373 73.0449 45.9376C74.0949 46.638 75.3304 47.008 76.5925 47.0002C80.0122 47.0002 82.9027 44.9917 82.9027 40.0832V28.1571H80.1144Z" fill="#202124"/>
    <path d="M119.972 21.0854H110.129V40.6629H119.972V21.0854Z" fill="#428EFF"/>
    <path d="M138.23 40.9728C143.808 40.9728 148.329 36.4512 148.329 30.8736C148.329 25.296 143.808 20.7744 138.23 20.7744C132.652 20.7744 128.131 25.296 128.131 30.8736C128.131 36.4512 132.652 40.9728 138.23 40.9728Z" fill="#428EFF"/>
    <path d="M123.2 42.7473H121.303L126.703 19H128.601L123.2 42.7473Z" fill="#202124"/>
    </g>
    <defs>
    <clipPath id="clip0_3949_6913">
    <rect width="128.329" height="28" fill="white" transform="translate(20 19)"/>
    </clipPath>
    </defs>
  </svg>
  
  
  <svg
    id="medium-dark-logo"
    class="hidden dark:block dark-logo"
    aria-hidden="true"
    alt=""
    role="presentation"
    width="154"
    height="64"
    viewBox="0 0 154 64"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g clip-path="url(#clip0_3947_14983)">
    <path d="M20 30.7235C20 25.0386 24.768 20.4086 30.4633 20.4086C31.7722 20.3867 33.0723 20.6268 34.2871 21.1148C35.5018 21.6028 36.6067 22.3288 37.5367 23.2502L35.5387 25.2386C34.1782 23.9273 32.3554 23.2055 30.4659 23.2301C26.318 23.2301 23.0756 26.5703 23.0756 30.727C23.0756 34.8836 26.3128 38.2221 30.4659 38.2221C33.1564 38.2221 34.689 37.141 35.6705 36.1586C36.4757 35.3526 37.0023 34.1929 37.204 32.621H30.4633V29.7917H39.9416C40.0491 30.3752 40.0997 30.9677 40.0927 31.5609C40.0927 33.6733 39.5155 36.2887 37.6537 38.1514C35.8391 40.0297 33.525 41.0261 30.4633 41.0261C24.768 41.0261 20 36.4083 20 30.7217" fill="#E8EAED"/>
    <path d="M47.7491 38.4181C45.7406 38.4181 44.0046 36.7589 44.0046 34.3933C44.0046 32.0276 45.738 30.3693 47.7491 30.3693C49.7602 30.3693 51.4909 32.004 51.4909 34.3967C51.4909 36.7895 49.7575 38.4198 47.7491 38.4198V38.4181ZM47.7491 27.7557C44.0814 27.7557 41.0879 30.5501 41.0879 34.3924C41.0879 38.2347 44.0788 41.0247 47.7491 41.0247C51.4193 41.0247 54.4111 38.2068 54.4111 34.388C54.4111 30.5693 51.4167 27.7539 47.7491 27.7539V27.7557Z" fill="#E8EAED"/>
    <path d="M62.2792 38.4181C60.2708 38.4181 58.5339 36.7589 58.5339 34.3933C58.5339 32.0276 60.2681 30.3693 62.2792 30.3693C64.2903 30.3693 66.0246 32.004 66.0246 34.3967C66.0246 36.7895 64.2903 38.4233 62.2792 38.4233V38.4181ZM62.2792 27.7591C58.6116 27.7591 55.6172 30.5536 55.6172 34.3959C55.6172 38.2382 58.609 41.0282 62.2792 41.0282C65.9495 41.0282 68.9413 38.2103 68.9413 34.3915C68.9413 30.5728 65.9495 27.7539 62.2792 27.7539V27.7591Z" fill="#E8EAED"/>
    <path d="M87.8112 21.1143H84.8945V40.6332H87.8112V21.1143Z" fill="#E8EAED"/>
    <path d="M87.8112 21.1143H84.8945V40.6332H87.8112V21.1143Z" fill="#E8EAED"/>
    <path d="M95.5802 30.3207C96.7372 30.3207 97.717 30.8979 98.0428 31.7292L92.1107 34.1935C92.0339 31.627 94.0965 30.3207 95.5793 30.3207H95.5802ZM95.8055 38.4201C94.3209 38.4201 93.266 37.7407 92.5884 36.4116L101.464 32.7378L101.166 31.9894C100.612 30.5049 98.9291 27.7646 95.4841 27.7646C92.0391 27.7646 89.2246 30.4569 89.2246 34.4014C89.2246 38.124 92.0409 41.0381 95.8116 41.0381C96.9056 41.0437 97.9838 40.7774 98.9494 40.2629C99.9149 39.7484 100.737 39.002 101.343 38.0909L99.0802 36.5819C98.3196 37.6857 97.2891 38.4201 95.8063 38.4201H95.8055Z" fill="#E8EAED"/>
    <path d="M76.7785 38.4205C74.7701 38.4205 73.0829 36.7351 73.0829 34.4219C73.0829 32.1086 74.7674 30.3717 76.7785 30.3717C78.7896 30.3717 80.3135 32.0815 80.3135 34.4219C80.3135 36.7622 78.7608 38.4205 76.7751 38.4205H76.7785ZM80.1144 28.1571V29.2365H80.0139C79.3599 28.4506 78.1033 27.752 76.5209 27.752C73.2026 27.752 70.1602 30.6704 70.1602 34.4184C70.1602 38.1664 73.2017 41.0263 76.5209 41.0263C78.1041 41.0263 79.3608 40.3277 80.0139 39.5173H80.1144V40.4726C80.1144 43.0129 78.7573 44.3708 76.5786 44.3708C74.7936 44.3708 73.6881 43.088 73.2401 42.0131L70.7007 43.0706C71.1784 44.2388 71.9949 45.2373 73.0449 45.9376C74.0949 46.638 75.3304 47.008 76.5925 47.0002C80.0122 47.0002 82.9027 44.9917 82.9027 40.0832V28.1571H80.1144Z" fill="#E8EAED"/>
    <path d="M119.972 21.085H110.129V40.6624H119.972V21.085Z" fill="#4285F4"/>
    <path d="M138.23 40.9728C143.808 40.9728 148.329 36.4512 148.329 30.8736C148.329 25.296 143.808 20.7744 138.23 20.7744C132.652 20.7744 128.131 25.296 128.131 30.8736C128.131 36.4512 132.652 40.9728 138.23 40.9728Z" fill="#4285F4"/>
    <path d="M123.2 42.7473H121.303L126.703 19H128.601L123.2 42.7473Z" fill="#E8EAED"/>
    </g>
    <defs>
    <clipPath id="clip0_3947_14983">
    <rect width="128.329" height="28" fill="white" transform="translate(20 19)"/>
    </clipPath>
    </defs>
  </svg>
    
  
  <svg
    id="medium-onsite-logo"
    class="hidden onsite-logo dark:hidden"
    aria-hidden="true"
    alt=""
    role="presentation"
    width="174"
    height="64"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g clip-path="url(#a)" fill="#202124"><path d="M20.79 30.724c0-5.685 4.768-10.315 10.463-10.315a9.817 9.817 0 0 1 7.074 2.841l-1.998 1.989a7.175 7.175 0 0 0-5.073-2.009c-4.148 0-7.39 3.34-7.39 7.497s3.237 7.495 7.39 7.495c2.69 0 4.223-1.081 5.205-2.063.805-.806 1.331-1.966 1.533-3.538h-6.74v-2.83h9.478c.107.584.158 1.177.15 1.77 0 2.112-.576 4.728-2.438 6.59-1.815 1.879-4.129 2.875-7.19 2.875-5.696 0-10.464-4.618-10.464-10.304M48.54 38.418c-2.01 0-3.745-1.66-3.745-4.025s1.733-4.024 3.744-4.024 3.742 1.635 3.742 4.028c0 2.392-1.733 4.023-3.742 4.023v-.002Zm0-10.662c-3.668 0-6.662 2.794-6.662 6.636 0 3.843 2.991 6.633 6.661 6.633 3.67 0 6.662-2.818 6.662-6.637 0-3.819-2.994-6.634-6.662-6.634v.002ZM63.07 38.418c-2.009 0-3.746-1.66-3.746-4.025s1.734-4.024 3.745-4.024c2.012 0 3.746 1.635 3.746 4.028 0 2.392-1.734 4.026-3.745 4.026v-.005Zm0-10.659c-3.668 0-6.663 2.795-6.663 6.637 0 3.842 2.992 6.632 6.663 6.632 3.67 0 6.662-2.818 6.662-6.636 0-3.82-2.992-6.638-6.663-6.638v.005ZM88.602 21.114h-2.917v19.52h2.917v-19.52Z"/><path d="M88.602 21.114h-2.917v19.52h2.917v-19.52ZM96.37 30.32c1.157 0 2.137.578 2.463 1.41L92.9 34.192c-.077-2.566 1.986-3.872 3.468-3.872h.001Zm.225 8.1c-1.484 0-2.539-.68-3.217-2.008l8.876-3.674-.298-.749c-.554-1.484-2.237-4.224-5.682-4.224-3.445 0-6.26 2.692-6.26 6.636 0 3.723 2.817 6.637 6.588 6.637a6.6 6.6 0 0 0 5.531-2.947l-2.263-1.51c-.76 1.105-1.79 1.84-3.274 1.84ZM77.57 38.42c-2.01 0-3.696-1.685-3.696-3.998s1.684-4.05 3.695-4.05 3.535 1.71 3.535 4.05-1.553 3.998-3.538 3.998h.003Zm3.335-10.263v1.08h-.1c-.655-.786-1.911-1.485-3.494-1.485-3.318 0-6.36 2.918-6.36 6.666s3.041 6.608 6.36 6.608c1.584 0 2.84-.698 3.493-1.509h.1v.956c0 2.54-1.356 3.898-3.535 3.898-1.785 0-2.89-1.283-3.338-2.358l-2.54 1.058A6.324 6.324 0 0 0 77.383 47c3.42 0 6.31-2.01 6.31-6.918V28.157h-2.788ZM120.763 21.085h-9.844v19.577h9.844V21.085ZM139.02 40.973c5.577 0 10.099-4.522 10.099-10.1 0-5.577-4.522-10.099-10.099-10.099-5.578 0-10.1 4.522-10.1 10.1 0 5.577 4.522 10.099 10.1 10.099ZM123.99 42.747h-1.897l5.4-23.747h1.898l-5.401 23.747Z"/></g><defs><clipPath id="a"><path fill="#fff" transform="translate(20.79 19)" d="M0 0h128.329v28H0z"/></clipPath></defs>
  </svg>
</a>

    
    <div id="desktop-nav-links" class="hidden text-md:flex items-center justify-start flex-nowrap">
      
        <div class="nav-links inline md:s-button-default">
          <a href="/2023/watch/"
            langKey="global_watch"
            data-category="main-nav"
            data-action="Program"
            data-label="na"
          >
            Watch
          </a>
        </div>
      

      
        <div class="nav-links inline md:s-button-default">
          <a href="/2023/learn/"
            langKey="global_learn"
            data-category="main-nav"
            data-action="Learn"
            data-label="na"
          >
            Learn
          </a>
        </div>
      

      

      
      
        <div class="nav-links inline md:s-button-default">
          <a
            href="/2023/community/"
            target="_self"
            aria-label="Join a developer community group near you for networking, events, collaboration, and more."
            langKey="global_community"
            data-category="main-nav"
            data-action="Community"
            data-label="na"
          >
            Community
          </a>
        </div>
      

      

      
        <div class="nav-links inline md:s-button-default">
          <a href="/2023/about/"
            langKey="global_about"
            data-category="main-nav"
            data-action="About"
            data-label="na"
          >
            About
          </a>
        </div>
      
    </div>

    
    <div id="header-actions" class="flex ml-auto">
      
        
        <div class="h-onsite-header self-center" data-travel="True" data-schedule="True"><div class="hidden"><div class="block hidden absolute left-[22px] top-[81px] h-5 w-5"></div><div><a href="/2023/inpersonfaq/" aria-label="Shoreline event information" class="relative z-10 hidden md:block"><div class="inline-block text-grey-900 bg-yellow dark:bg-yellow-dark nav-button rounded-xl"><span>Shoreline </span></div></a><div class="gap-8 border-t-2 border-b-2 bg-yellow border-grey-900 dark:border-grey-200
    absolute left-0 w-full p-6 justify-center lg:justify-start lg:pl-60
    hidden" style="top: 74px;"><a href="/2023/inpersonfaq/" class="onsite-nav-links relative focus:outline-none focus-visible:outline-none focus:ring focus:ring-white" data-category="main-nav" data-action="Shoreline" data-label="Frequently Asked Questions"><span>Shoreline FAQ</span><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full block dark:hidden invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#ffffff"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#202124"></path></svg><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full hidden dark:block invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#5F6368"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#E8EAED"></path></svg></a><a href="/2023/health-safety/" class="onsite-nav-links relative focus:outline-none focus-visible:outline-none focus:ring focus:ring-white" data-category="main-nav" data-action="Shoreline" data-label="Health and Safety"><span>Health and Safety</span><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full block dark:hidden invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#ffffff"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#202124"></path></svg><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full hidden dark:block invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#5F6368"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#E8EAED"></path></svg></a><a href="/2023/travel/" class="onsite-nav-links relative focus:outline-none focus-visible:outline-none focus:ring focus:ring-white hidden" data-category="main-nav" data-action="Shoreline" data-label="Travel &amp; Accommodations"><span>Transportation and Logistics</span><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full block dark:hidden invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#ffffff"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#202124"></path></svg><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full hidden dark:block invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#5F6368"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#E8EAED"></path></svg></a><a href="/2023/schedule/" class="onsite-nav-links relative focus:outline-none focus-visible:outline-none focus:ring focus:ring-white hidden" data-category="main-nav" data-action="Shoreline" data-label="Schedule"><span class="hidden">Schedule and Map</span><span class>[EN-ONLY KEY MISSING/nt_schedule_pagetitle_phase3]</span><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full block dark:hidden invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#ffffff"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#202124"></path></svg><svg width="16" height="9" viewBox="0 0 16 9" fill="none" xmlns="http://www.w3.org/2000/svg" style="top: 41px; position: absolute;" aria-hidden="true" class="w-full hidden dark:block invisible hover:visible"><path d="M7.99777 3L14.3495 9H1.68695L7.99777 3Z" fill="#5F6368"></path><path fill-rule="evenodd" clip-rule="evenodd" d="M0 7H1.0205L8.01822 0L15.0159 7H16V9H14.3495L7.99777 3L1.68695 9H0V7Z" fill="#E8EAED"></path></svg></a></div></div></div></div>
      
      
      <div class="hidden text-md:flex items-center">
        <div class="h-choose-language" data-in-footer="">
	<select name="language-select" role="listbox" alt class="font-medium language-select focus-trapped bg-white dark:bg-grey-900 text-grey-900 dark:text-white w-full border-none pl-0 ml:w-32 ml:pl-4 sm:s-cta2 md:s-cta1">
		<option selected value="en"></option>
		<option value="es"></option>
		<option value="pt"></option>
		<option value="fr"></option>
		<option value="id"></option>
		<option value="ko"></option>
		<option value="zh"></option>
		<option value="ja"></option>
	</select>
	<div style="z-index: 10;" class="absolute  invisible">
		<div class="bg-white dark:bg-grey-900 dark:text-grey-200 border-2 border-grey-900 dark:border-grey-200 text-grey-900 sm:l-cta2 font-medium p-2 pr-6 w-full">
			<span></span>
			<button type="button" class="absolute top-0 bottom-0" aria-label="Close">
				<svg class="fill-current dark:fill-white text-grey-900 w-6 h-6 forced-white-color" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 18">
					<path d="m14.53 4.53-1.06-1.06L9 7.94 4.53 3.47 3.47 4.53 7.94 9l-4.47 4.47 1.06 1.06L9 10.06l4.47 4.47 1.06-1.06L10.06 9z"></path>
				</svg>
			</button>
		</div>
		<svg width="32" height="20" viewBox="-2 -2 37 28" fill="none" xmlns="http://www.w3.org/2000/svg" style="bottom: -18px; transform: scale(1, -1); right: 80px;" aria-hidden="true" class="absolute block dark:hidden hcm-hidden">
			<g id="Polygon 1">
				<path d="M0.138981 4.44226C0.0834319 1.0678 3.97439 -0.854559 6.62079 1.23988L35.9246 24.4317C37.4112 25.6083 36.5792 28 34.6834 28L2.49412 28C1.40238 28 0.512363 27.1245 0.494394 26.0329L0.138981 4.44226Z" fill="currentColor" stroke="#202124" stroke-width="2.5" mask="url(#path-1-inside-1_0_1)" class="arrow-white"></path>
			</g>
		</svg>
		<svg width="32" height="20" viewBox="-2 -2 37 28" fill="none" xmlns="http://www.w3.org/2000/svg" style="bottom: -18px; transform: scale(1, -1); right: 80px;" aria-hidden="true" class="absolute hidden dark:block hcm-block">
			<g id="Polygon 1">
				<path d="M0.138981 4.44226C0.0834319 1.0678 3.97439 -0.854559 6.62079 1.23988L35.9246 24.4317C37.4112 25.6083 36.5792 28 34.6834 28L2.49412 28C1.40238 28 0.512363 27.1245 0.494394 26.0329L0.138981 4.44226Z" fill="currentColor" stroke="#E8EAED" stroke-width="2.5" mask="url(#path-1-inside-1_0_1)" class="arrow-white"></path>
			</g>
		</svg>
	</div>
</div>
      </div>

      
        
        <div class="flex">
          <div class="hidden md:flex">
            <div class="h-header-actions flex justify-between" data-registration-available="False" data-myio-available="True"><div class="relative" style="width: 44px;"></div></div>
          </div>
          <div class="flex md:hidden">
            <div id="h-header-actions-mobile" class="flex self-center md:hidden text-grey-900 dark:text-grey-200" data-registration-available="False" data-myio-available="True"><div class="relative mr-5"><span class=" block margin-0"><svg class="loading__circular " viewBox="25 25 50 50"><circle class="loading__path " cx="50" stroke-linecap="butt" cy="50" r="20" fill="none" stroke-width="5" stroke-miterlimit="10"></circle></svg></span></div></div>
          </div>
        </div>
      
      
      
      
    </div>

    
    <div class="h-data-layer"><div class="hidden"></div></div>
  </nav>
  <script defer>
    const activePage = window.location.pathname;
    if (!isHome()) {
      highlightActivePageLink();
    } else {
      highlightClickableLinks();
    }

    function highlightClickableLinks() {
      document.querySelectorAll("[data-active]").forEach((link) => {
        link.classList.add("active");
      });
    }

    function highlightActivePageLink() {
      //TO-DO: Need to work out a more modular implementation of this
      highlightClickableLinks();
      document
        .querySelectorAll(".nav-links, .sub-nav-links, .active-helper")
        .forEach((link) => {
          //Adding underline to About nav item  when a subnav item is active
          if (
            typeof link.href !== "undefined" &&
            link.href.includes(`${activePage}`)
          ) {
            if (
              link.href.includes("/2023/about/") ||
              link.href.includes("/2023/faq/") ||
              link.href.includes("/2023/community/")
            ) {
              document.querySelectorAll("[data-active]").forEach((link) => {
                link.innerHTML.includes("About")
                  ? link.classList.add("active-underline")
                  : null;
              });
            }
            link.classList.add("active-underline");
          }
        });
    }

    function isHome() {
      if (activePage === "/2023/") {
        return true;
      }
      const es = new RegExp(/^\/intl\/es\/$/);
      const fr = new RegExp(/^\/intl\/fr\/$/);
      const pt = new RegExp(/^\/intl\/pt\/$/);
      const id = new RegExp(/^\/intl\/id\/$/);
      const ko = new RegExp(/^\/intl\/ko\/$/);
      const zh = new RegExp(/^\/intl\/zh\/$/);
      const ja = new RegExp(/^\/intl\/ja\/$/);

      switch (true) {
        case es.test(activePage):
          return true;
        case fr.test(activePage):
          return true;
        case pt.test(activePage):
          return true;
        case id.test(activePage):
          return true;
        case ko.test(activePage):
          return true;
        case zh.test(activePage):
          return true;
        case ja.test(activePage):
          return true;

        default:
          return false;
      }
    }
  </script>
</header>
  <main id="content" class="dark:bg-grey-900 flex-1">
<div class="hidden">
  Google I/O 2023
  Google I/O 2023
  Tune in to watch the latest news and innovations from Google. Join I/O for livestreamed keynotes and helpful product updates on demand.

  Tune in to watch the latest news and innovations from Google. Join I/O for livestreamed keynotes and helpful product updates on demand.

</div>






<div class="page-wrapper flex flex-col gap-6">
  
  <div class="flex items-center justify-center">
    <div class="flex flex-col relative rounded-2xl bg-grey-900 border-2 border-grey-900  dark:border-grey-200 overflow-hidden w-full md:flex-row text-md:min-h-[407px] max-w-xl">
      
      <div class="flex flex-col px-6 pb-6 pt-8 md:w-1/2 md:p-10">
        <h1 class="font-medium text-white mb-4 sm:s-h3 md:l-h2 w-[85%]">
          And that's a wrap! Thanks for joining Google I/O 2023
        </h1>
        <div class="flex-1 flex flex-col justify-between items-start gap-4">
          <p class="font-medium text-white  sm:s-h6 md:l-h6">
            And that's a wrap! Thanks for joining Google I/O 2023
          </p>
          <a
            href="https://google.qualtrics.com/jfe/form/SV_204I0exwGsruwgC"
            class="cta-blue-btn cta-btn-spacing"
            aria-label="Take the Google I/O 2023 survey"
            target="_blank"
            rel="noopener"
            data-analytics-event="cta_survey"
            data-analytics-event-data='{"cta_position": "body"}'
          >
            Take the survey
          </a>
        </div>
      </div>
      
      <div class="flex justify-center md:w-1/2">
        
        <div class="hidden w-full text-md:flex">
          <img
            class="w-full h-full object-cover object-left"
            src="/2023/app/images/wrap-hero-homepage.svg"
            role="img"
            aria-hidden="true"
          />
        </div>
        
        <div class="flex w-full text-md:hidden">
          <img
            class="w-full h-full object-cover object-left"
            src="/2023/app/images/wrap-hero-homepage-mobile.svg"
            role="img"
            aria-hidden="true"
          />
        </div>
      </div>
    </div>
  </div>

  
  
    <div class="flex flex-col align-center items-stretch justify-center gap-2 md:flex-row mt-12 md:mt-[40px]">
      
        <div class="flex w-full md:w-1/2">
  <div class="flex-1 flex flex-col border-2 bg-grey-200 border-grey-900 rounded-2xl md:flex-row">
    <div class="flex-1 flex flex-col items-start p-6 ml:p-10 ml:pr-0">
      <div class="font-medium text-black mb-5 sm:s-h3 md:l-h4 md:mb-6">
        I/O Connect
      </div>
      <div class="flex-1 flex flex-col justify-between items-start">
        <p class="font-medium text-black mb-7 sm:s-h5 md:l-h6">
          Join sessions, office hours, and demos at Google's in-person developer events.
        </p>
        <div onclick="trackEvent('cta_connect', {cta_position: 'body'})">
          
            
            
            
            <div class="h-external-link" data-id="community_connnect_cta" data-styles="cta-ghost-btn cta-btn-spacing hover:!bg-blue focus:!bg-blue" data-aria="home_a_connect_cta_a11y" data-alt="" data-newtab=""><span></span></div>
          
        </div>
      </div>
    </div>
    <div class="flex justify-end p-[24px] md:hidden ml:flex ml:w-1/2 ml:p-[30px]">
      <img src="/2023/app/images/find-an-event.svg" width="311" height="302" class="object-contain" role="img" aria-hidden="true">
    </div>
  </div>
</div>
      
        
  
    
    
  
  <div class="flex w-full md:w-1/2">
    <div class="flex-1 flex flex-col overflow-hidden border-2 border-grey-900 rounded-2xl md:flex-row bg-blue font-medium text-black">
      <div class="flex-1 flex flex-col items-start p-6 ml:p-10 ml:pr-0">
        <div class="font-medium mb-5 sm:s-h3 md:l-h4 md:mb-6">
          I/O Extended
        </div>
        <div class="flex-1 flex flex-col justify-between items-start">
          <p class="font-medium mb-7 sm:s-h5 md:l-h6">
            Celebrate I/O technology with a local community-led event near you.
          </p>
          <div onclick="trackEvent('cta_extend', {cta_position: 'body'})">
            
              
              
              
              <div class="h-external-link" data-id="community_extended_cta" data-styles="cta-btn-spacing  cta-ghost-btn" data-aria="home_a_extended_cta_a11y" data-alt="" data-newtab=""><span></span></div>
            
          </div>
        </div>
      </div>
      <div class="flex justify-end pt-12 md:hidden ml:flex ml:w-1/2">
        <img src="/2023/app/images/extend-cta.svg" width="367" height="314" class="-mb-24 object-cover object-left ml:mb-0" role="img" aria-hidden="true">
      </div>
    </div>
  </div>

      
    </div>
  

  
  




<div class="mt-16 dark:text-grey-200 ml:px-18">
  <div class="grid grid-cols-1 md:grid-cols-3 gap-x-8 ">
    
      
      <div class="hover-outline mx-2 md:mx-0 focus-within:hover-outline">
        <div class="w-full p-4 md:p-5">
          <a
            href="http://www.youtube.com/watch_videos?video_ids=QpBTM0GO6xI,hleLlcHwQLM"
            rel="noopener noreferrer"
            target="_blank"
            class="focus:outline-none focus-visible:outline-none"
            onclick="trackEvent('cta_watch_recap', {cta_position: 'body'})"
          >
            <div class="w-full aspect-w-16 aspect-h-9 relative mb-5">
              <img
                src="/2023/app/images/recap-video-list.png"
                class="absolute h-full w-full object-cover session-image rounded-xl"
                loading="lazy"
                role="img"
                aria-hidden="true"
              >
            </div>
            <div class="mb-4">
              <div class="font-medium sm:s-h4 md:l-h5 my-2">
                Watch the recap videos
              </div>
            </div>
          </a>
        </div>
      </div>
    

    
    
      
        






    
    
    
    

    
        
    
    
    
    

    
    
    
        
    
    

    
        
    
    
    
    

    
        
    
    
    
    

    
    
    
    
        
            
        
    

    
        
    
    
    
    

<div
  role=""
  class="hover-outline mx-2 md:mx-0 focus-within:hover-outline   session"
  
    data-session-id="396cd2d5-9fe1-4725-a3dc-c01bb2e2f38a"
    data-topic="[]"
    data-level="[&#34;d3e15c80-37c4-4ea7-b2bd-5c23f3042b01&#34;]"
    data-type="[&#34;keynote-filter&#34;]"
    data-stack="[&#34;4c5c12d4-a585-498c-8425-1d7f143c2ade&#34;, &#34;88702022-d7d1-4351-ba8d-66cbf9aa4adc&#34;, &#34;ae6b197a-28d3-432b-85b2-9d764c8092d6&#34;, &#34;697d7328-cf90-4edc-84c1-f4954328264b&#34;]"
  
>
  <div class="w-full p-4 md:p-5">
    <a
      
      
      
      
      href="/2023/program/396cd2d5-9fe1-4725-a3dc-c01bb2e2f38a/"
      
      
      onclick="trackEvent('cta_google_io_keynote', {cta_position: 'body'})"
      
      class="focus:outline-none focus-visible:outline-none"
      >
        
        
          <div class="w-full aspect-w-16 aspect-h-9 relative mb-5">
            
            <img loading="lazy" role="img" aria-hidden="true" class="absolute h-full w-full object-cover rounded-xl" src="/2023/data/im/396cd2d5-9fe1-4725-a3dc-c01bb2e2f38a.webp" />
          </div>
        

        
        <div class="mb-4">
          
            <div class="font-medium sm:s-h4 my-2 md:l-h5">
              Google keynote
            </div>
          
        </div>
      </a>
        
        <div class="flex mt-auto flex-col gap-2 sm:flex-row sm:gap-9 md:flex-col md:gap-2 lg:flex-row lg:gap-9">
            
          
            
              
              
                
                  <div class="r-bookmark" data-bm-session-id="396cd2d5-9fe1-4725-a3dc-c01bb2e2f38a" data-session-path="" data-disable-dark-mode="False" data-white-spinner="" data-myio-label="True" data-label-position="" data-title="Google keynote" data-category="">
	<span class="hidden block margin-0">
		<svg class="loading__circular " viewBox="25 25 50 50">
			<circle class="loading__path " cx="50" stroke-linecap="butt" cy="50" r="20" fill="none" stroke-width="5" stroke-miterlimit="10"></circle>
		</svg>
	</span>
	<button type="button" disabled aria-label class="hidden">
		<span class="flex justify-center items-center w-6 h-6">
			<svg width="16" height="20" viewBox="0 0 16 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="forced-white-color  opacity-50 hcm-opacity ">
				<path d="M1 1V19L7.07895 14.5L14.2632 19V1H1Z" stroke="#202124" stroke-width="1.5" stroke-linejoin="round" class="hcm-link-text-stroke stroke-grey-900 dark:stroke-grey-200"></path>
			</svg>
		</span>
	</button>
</div>
                
              
            
          
        </div>
    </div>
</div>
      
    
    
      
        






    
    
    
    

    
        
    
    
    
    

    
    
    
        
    
    

    
        
    
    
    
    

    
        
    
    
    
    

    
    
    
    
        
            
        
    

    
        
    
    
    
    

<div
  role=""
  class="hover-outline mx-2 md:mx-0 focus-within:hover-outline   session"
  
    data-session-id="9fe491dd-cadc-4e03-b084-f75e695993ea"
    data-topic="[]"
    data-level="[&#34;d3e15c80-37c4-4ea7-b2bd-5c23f3042b01&#34;]"
    data-type="[&#34;keynote-filter&#34;]"
    data-stack="[&#34;4c5c12d4-a585-498c-8425-1d7f143c2ade&#34;, &#34;88702022-d7d1-4351-ba8d-66cbf9aa4adc&#34;, &#34;ae6b197a-28d3-432b-85b2-9d764c8092d6&#34;, &#34;697d7328-cf90-4edc-84c1-f4954328264b&#34;]"
  
>
  <div class="w-full p-4 md:p-5">
    <a
      
      
      
      
      href="/2023/program/9fe491dd-cadc-4e03-b084-f75e695993ea/"
      
      
      onclick="trackEvent('cta_developer_keynote', {cta_position: 'body'})"
      
      class="focus:outline-none focus-visible:outline-none"
      >
        
        
          <div class="w-full aspect-w-16 aspect-h-9 relative mb-5">
            
            <img loading="lazy" role="img" aria-hidden="true" class="absolute h-full w-full object-cover rounded-xl" src="/2023/data/im/9fe491dd-cadc-4e03-b084-f75e695993ea.webp" />
          </div>
        

        
        <div class="mb-4">
          
            <div class="font-medium sm:s-h4 my-2 md:l-h5">
              Developer keynote
            </div>
          
        </div>
      </a>
        
        <div class="flex mt-auto flex-col gap-2 sm:flex-row sm:gap-9 md:flex-col md:gap-2 lg:flex-row lg:gap-9">
            
          
            
              
              
                
                  <div class="r-bookmark" data-bm-session-id="9fe491dd-cadc-4e03-b084-f75e695993ea" data-session-path="" data-disable-dark-mode="False" data-white-spinner="" data-myio-label="True" data-label-position="" data-title="Developer keynote" data-category="">
	<span class="hidden block margin-0">
		<svg class="loading__circular " viewBox="25 25 50 50">
			<circle class="loading__path " cx="50" stroke-linecap="butt" cy="50" r="20" fill="none" stroke-width="5" stroke-miterlimit="10"></circle>
		</svg>
	</span>
	<button type="button" disabled aria-label class="hidden">
		<span class="flex justify-center items-center w-6 h-6">
			<svg width="16" height="20" viewBox="0 0 16 20" fill="none" xmlns="http://www.w3.org/2000/svg" class="forced-white-color  opacity-50 hcm-opacity ">
				<path d="M1 1V19L7.07895 14.5L14.2632 19V1H1Z" stroke="#202124" stroke-width="1.5" stroke-linejoin="round" class="hcm-link-text-stroke stroke-grey-900 dark:stroke-grey-200"></path>
			</svg>
		</span>
	</button>
</div>
                
              
            
          
        </div>
    </div>
</div>
      
    
  </div>
</div>

  
  


<div class="flex flex-col mt-12 md:px-9">
  <div class="flex flex-row justify-between mx-6 md:mx-0">
    <h2 class="font-medium text-left w-3/5 text-grey-900 mb-8 sm:s-h3 md:l-h3 md:w-auto dark:text-grey-200">
      What are you developing for?
    </h2>
    <a
      href="/2023/program/"
      aria-label="Opens Program page"
      class="cta-link-btn mt-3 hidden md:inline-block"
      data-analytics-event="view_all"
      data-analytics-event-data='{"moduleName": "program"}'
    >
      View all content
    </a>
  </div>
  <div class="grid md:grid-cols-2 lg:grid-cols-4 lg:justify-items-center">
    
    
    
    
  
  <a
    href="/2023/program/?q=mobile"
    data-analytics-event="content_card_select"
    data-analytics-event-data='{"cardName": "mobile"}'
    aria-label="Jumplink Filter content by mobile focus."
    class="mb-0 w-full basis-full inline-block rounded-3xl p-4 border-2 border-transparent hover:border-grey-900 focus:border-grey-900 dark:hover:border-grey-200 dark:focus:border-grey-200 focus:outline-none group">
    <img
      src="/2023/app/images/stacks_mobile.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full group-hover:hidden"
    />
    <img
      src="/2023/app/images/stacks_mobile-hover.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full hidden group-hover:block"
    />
    <div class="text-grey-900 mt-6 dark:text-grey-200">
      <h3 class="font-medium mb-3 sm:s-h4 md:l-h4">
        Mobile  
      </h3>
      <p class="font-normal sm:s-p2 md:l-p2">Develop for a range of audiences and form factors.</p>
    </div>
  </a>
    
    
    
    
  
  <a
    href="/2023/program/?q=web"
    data-analytics-event="content_card_select"
    data-analytics-event-data='{"cardName": "web"}'
    aria-label="Jumplink Filter content by web focus."
    class="mb-0 w-full basis-full inline-block rounded-3xl p-4 border-2 border-transparent hover:border-grey-900 focus:border-grey-900 dark:hover:border-grey-200 dark:focus:border-grey-200 focus:outline-none group">
    <img
      src="/2023/app/images/stacks_web.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full group-hover:hidden"
    />
    <img
      src="/2023/app/images/stacks_web-hover.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full hidden group-hover:block"
    />
    <div class="text-grey-900 mt-6 dark:text-grey-200">
      <h3 class="font-medium mb-3 sm:s-h4 md:l-h4">
        Web
      </h3>
      <p class="font-normal sm:s-p2 md:l-p2">Create fast, secure sites and apps for the open web.</p>
    </div>
  </a>
    
    
    
    
  
  <a
    href="/2023/program/?q=ai"
    data-analytics-event="content_card_select"
    data-analytics-event-data='{"cardName": "ai"}'
    aria-label="Jumplink Filter content by AI focus."
    class="mb-0 w-full basis-full inline-block rounded-3xl p-4 border-2 border-transparent hover:border-grey-900 focus:border-grey-900 dark:hover:border-grey-200 dark:focus:border-grey-200 focus:outline-none group">
    <img
      src="/2023/app/images/stacks_ai.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full group-hover:hidden"
    />
    <img
      src="/2023/app/images/stacks_ai-hover.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full hidden group-hover:block"
    />
    <div class="text-grey-900 mt-6 dark:text-grey-200">
      <h3 class="font-medium mb-3 sm:s-h4 md:l-h4">
        AI 
      </h3>
      <p class="font-normal sm:s-p2 md:l-p2">Bring the power of machine learning to apps and workflows.</p>
    </div>
  </a>
    
    
    
    
  
  <a
    href="/2023/program/?q=cloud"
    data-analytics-event="content_card_select"
    data-analytics-event-data='{"cardName": "cloud"}'
    aria-label="Jumplink Filter content by cloud focus."
    class="mb-0 w-full basis-full inline-block rounded-3xl p-4 border-2 border-transparent hover:border-grey-900 focus:border-grey-900 dark:hover:border-grey-200 dark:focus:border-grey-200 focus:outline-none group">
    <img
      src="/2023/app/images/stacks_cloud.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full group-hover:hidden"
    />
    <img
      src="/2023/app/images/stacks_cloud-hover.svg"
      width="303"
      height="170"
      role="img"
      aria-hidden="true"
      class="w-full hidden group-hover:block"
    />
    <div class="text-grey-900 mt-6 dark:text-grey-200">
      <h3 class="font-medium mb-3 sm:s-h4 md:l-h4">
        Cloud
      </h3>
      <p class="font-normal sm:s-p2 md:l-p2">Simplify and scale end-to-end development.</p>
    </div>
  </a>
  </div>
  <a
    href="/2023/program/"
    aria-label="Opens Program page"
    class="cta-link-btn mt-11 text-center inline-block md:hidden"
    data-analytics-event="view_all"
    data-analytics-event-data='{"moduleName": "program"}'
  >
    View all content
  </a>
</div>

  
  


<div class="flex flex-col mt-12 md:px-9">
  <div class="flex flex-row justify-between">
    <h3 class="font-medium text-left w-3/5 text-grey-900 mb-8 sm:s-h3 md:l-h3 md:w-auto dark:text-grey-200">
      Grow your skills
    </h3>
    <div class="cta-link-btn mt-3 hidden md:inline-block">
      <p><a href="/2023/learn/">View all learning material</a></p>
    </div>
  </div>
  <div class="grid md:grid-cols-3 gap-4 md:justify-items-center">
    
    <a
    href="/2023/program/?q=codelab,learning-pathway"
    data-analytics-event="content_card_select"
    data-analytics-event-data='{"cardName": "codelab"}'
    class="mb-0 inline-block rounded-xl p-6 bg-grey-200 md:max-w-[407px]">
    <img
      src="/2023/app/images/codelabs-icon.svg"
      class="w-[84px] h-[80px]"
      role="img"
      aria-hidden="true"
    />
    <div class="text-black mt-6">
      <h3 class="font-medium mb-3 sm:s-h5 md:l-h5">
        Codelabs and pathways
      </h3>
      <p class="font-normal sm:s-p2 md:l-p2">Start building today with self-paced coding exercises.</p>
    </div>
  </a>
    
    <a
    href="/2023/program/?q=workshop"
    data-analytics-event="content_card_select"
    data-analytics-event-data='{"cardName": "workshop"}'
    class="mb-0 inline-block rounded-xl p-6 bg-grey-200 md:max-w-[407px]">
    <img
      src="/2023/app/images/workshops-icon.svg"
      class="w-[84px] h-[80px]"
      role="img"
      aria-hidden="true"
    />
    <div class="text-black mt-6">
      <h3 class="font-medium mb-3 sm:s-h5 md:l-h5">
        Workshops
      </h3>
      <p class="font-normal sm:s-p2 md:l-p2">Gain skills with guided codelabs led by Google experts.</p>
    </div>
  </a>
    
    <a
    href="/2023/program/?q=demo"
    data-analytics-event="content_card_select"
    data-analytics-event-data='{"cardName": "demo"}'
    class="mb-0 inline-block rounded-xl p-6 bg-grey-200 md:max-w-[407px]">
    <img
      src="/2023/app/images/demos-icon.svg"
      class="w-[84px] h-[80px]"
      role="img"
      aria-hidden="true"
    />
    <div class="text-black mt-6">
      <h3 class="font-medium mb-3 sm:s-h5 md:l-h5">
        Product demos
      </h3>
      <p class="font-normal sm:s-p2 md:l-p2">Discover how Google's developer products work. </p>
    </div>
  </a>
  </div>
  <div class="cta-link-btn mt-11 text-center inline-block md:hidden">
    <p><a href="/2023/learn/">View all learning material</a></p>
  </div>
</div>

  
  <div class="flex flex-col mt-12 border-2 min-h-[360px] border-grey-900 rounded-2xl relative overflow-hidden bg-grey-900 dark:border-grey-200">
  <img src="/2023/app/images/seeyounextyear-mobile.svg" class="md:hidden" role="img" aria-hidden="true">
  <img src="/2023/app/images/seeyounextyear.svg" class="hidden md:block absolute left-0 bottom-0 w-full h-full" role="img" aria-hidden="true">
  <h3 class="text-white absolute max-w-[200px] left-[40px] top-[40px] sm:s-h2 md:l-h1 text-md:max-w-[615px]">
    See you next year
  </h3>
</div>

</div>

</main>
  <footer
  id="footer"
  class="pt-10 pb-16 lg:py-10 px-7 lg:px-16 bg-grey-900 flex flex-col lg:flex-row lg:justify-between lg:items-center w-max-full"
>
  <div
    class="flex flex-col lg:flex-row items-start lg:items-center space-y-6 lg:space-y-0 lg:space-x-6 text-grey-500 text-[16px] font-medium flex-1"
  >
    <div
      class="text-2xl font-semibold lg:mr-12 text-grey-500 flex justify-between w-full mb-4 lg:mb-0 lg:w-16"
    >
      <a href="https://www.google.com/" target="_blank" alt="Google home page">Google</a>
      
      <div class="lg:hidden">
        <div class="h-theme-toggle">
	<button class="p-3" aria-label="Toggle visual mode" role="button" tabIndex="0">
		<img src="/2023/app/images/ic_darkmode.svg" aria-hidden="true" width="24" height="24" />
	</button>
</div>
      </div>
    </div>

    <a href="https://io.google/2022/" target="_blank" rel="noreferrer noopener">
      I/O 2022
    </a>

    
      <a href="/2023/puzzle/" target="_blank" rel="noreferrer noopener">
        I/O Puzzle
      </a>
    

    <a href="https://policies.google.com/" target="_blank" rel="noreferrer noopener">
      Privacy & terms
    </a>
    <a
      href="https://developers.google.com/community-guidelines"
      target="_blank"
      rel="noreferrer noopener"
    >
      Community guidelines
    </a>
    <a href="/2023/about/#section-one">FAQ</a>
    
      <div class="h-choose-language" data-in-footer="True">
	<select name="language-select" role="listbox" alt class="font-medium language-select focus-trapped bg-white dark:bg-grey-900 text-grey-900 dark:text-white w-full border-none pl-0 ml:w-32 ml:pl-4 sm:s-cta2 md:s-cta1">
		<option selected value="en"></option>
		<option value="es"></option>
		<option value="pt"></option>
		<option value="fr"></option>
		<option value="id"></option>
		<option value="ko"></option>
		<option value="zh"></option>
		<option value="ja"></option>
	</select>
	<div style="z-index: 10;" class="absolute  invisible">
		<div class="bg-white dark:bg-grey-900 dark:text-grey-200 border-2 border-grey-900 dark:border-grey-200 text-grey-900 sm:l-cta2 font-medium p-2 pr-6 w-full">
			<span></span>
			<button type="button" class="absolute top-0 bottom-0" aria-label="Close">
				<svg class="fill-current dark:fill-white text-grey-900 w-6 h-6 forced-white-color" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 18 18">
					<path d="m14.53 4.53-1.06-1.06L9 7.94 4.53 3.47 3.47 4.53 7.94 9l-4.47 4.47 1.06 1.06L9 10.06l4.47 4.47 1.06-1.06L10.06 9z"></path>
				</svg>
			</button>
		</div>
		<svg width="32" height="20" viewBox="-2 -2 37 28" fill="none" xmlns="http://www.w3.org/2000/svg" style="bottom: -18px; transform: scale(1, -1); right: 80px;" aria-hidden="true" class="absolute block dark:hidden hcm-hidden">
			<g id="Polygon 1">
				<path d="M0.138981 4.44226C0.0834319 1.0678 3.97439 -0.854559 6.62079 1.23988L35.9246 24.4317C37.4112 25.6083 36.5792 28 34.6834 28L2.49412 28C1.40238 28 0.512363 27.1245 0.494394 26.0329L0.138981 4.44226Z" fill="currentColor" stroke="#202124" stroke-width="2.5" mask="url(#path-1-inside-1_0_1)" class="arrow-white"></path>
			</g>
		</svg>
		<svg width="32" height="20" viewBox="-2 -2 37 28" fill="none" xmlns="http://www.w3.org/2000/svg" style="bottom: -18px; transform: scale(1, -1); right: 80px;" aria-hidden="true" class="absolute hidden dark:block hcm-block">
			<g id="Polygon 1">
				<path d="M0.138981 4.44226C0.0834319 1.0678 3.97439 -0.854559 6.62079 1.23988L35.9246 24.4317C37.4112 25.6083 36.5792 28 34.6834 28L2.49412 28C1.40238 28 0.512363 27.1245 0.494394 26.0329L0.138981 4.44226Z" fill="currentColor" stroke="#E8EAED" stroke-width="2.5" mask="url(#path-1-inside-1_0_1)" class="arrow-white"></path>
			</g>
		</svg>
	</div>
</div>
    
  </div>

  <div class="flex lg:justify-self-end lg:justify-end mt-12 lg:mt-0">
    
    <a
      href="https://twitter.com/googledevs"
      class="p-3"
      target="_blank"
      rel="noreferrer noopener"
      aria-label="Google Developers on Twitter"
    >
      <img
        src="/2023/app/images/ic_twitter.svg"
        role="img"
        aria-hidden="true"
        height="24"
        width="24"
      />
    </a>
    
    <a
      href="https://www.linkedin.com/showcase/googledevelopers/"
      class="p-3"
      target="_blank"
      rel="noreferrer noopener"
      aria-label="Google Developers on LinkedIn"
    >
      <img
        src="/2023/app/images/ic_linkedin.svg"
        role="img"
        aria-hidden="true"
        height="24"
        width="24"
      />
    </a>
    
    <a
      href="https://developers.google.com/"
      class="p-3"
      target="_blank"
      rel="noreferrer noopener"
      aria-label="Google Developers Homepage"
    >
      <img
        src="/2023/app/images/ic_googledev.svg"
        role="img"
        aria-hidden="true"
        height="24"
        width="24"
      />
    </a>
    
    <a
      href="https://www.youtube.com/user/GoogleDevelopers"
      class="p-3"
      target="_blank"
      rel="noreferrer noopener"
      aria-label="Google Developers on YouTube"
    >
      <img
        src="/2023/app/images/ic_youtube.svg"
        role="img"
        aria-hidden="true"
        height="24"
        width="24"
      />
    </a>
    
    <a
      href="https://medium.com/google-developers"
      class="p-3"
      target="_blank"
      rel="noreferrer noopener"
      aria-label="Google Developers on Medium"
    >
      <img
        src="/2023/app/images/ic_medium.svg"
        role="img"
        aria-hidden="true"
        height="24"
        width="24"
      />
    </a>
    
    <div class="hidden lg:block">
      <div class="h-theme-toggle">
	<button class="p-3" aria-label="Toggle visual mode" role="button" tabIndex="0">
		<img src="/2023/app/images/ic_darkmode.svg" aria-hidden="true" width="24" height="24" />
	</button>
</div>
    </div>
  </div>
</footer>
  <script>
    window.iodata = {};
    window.iodata.creds = {};
    window.silence = function(){};
    window.iodata.phase = "phase4-1-post-event"
    window.iodata.public_keys = {
      oauth2_client_id: "724256043927-qqf2lu66l75hjqeg5po2mopuprg9ee0e.apps.googleusercontent.com",
      oauth2_api_key: "AIzaSyC9IlQdWjbDHPruCQ8p2erAH1SwsAldZnQ",
      youtube_api_key: "",
      googlemaps_api_key: "",
      devprofiles_endpoint: "https://developers.googleapis.com"
    };
    window.iodata.apis = {
      basePath: "/2023",
      users: "/2023/cgi-bin/users.aspx",
      reservations: "/2023/cgi-bin/reservations.aspx",
      capacity: "/2023/cgi-bin/capacity.aspx",
      alert: "https://storage.googleapis.com/io_extradata/alert.json"
    };
    window.iodata.gdg_gdsc = "/2023/data/community_data.json";
    window.iodata.sessions = "/2023/data/ep_topics2.json";
    window.iodata.sessions_new = "/2023/data/ep_bookmap.json";
    window.iodata.content_paths = "/2023/data/external.json";
    window.iodata.session_categories = "/2023/data/ep_categories.json";
  </script>
   
   <script>
    window.iodata.apis.extraData = "https://storage.googleapis.com/io_extradata/extra_data.json"
   </script>
   
  
  
  
  
  <script defer>
  /**
   * Phase1 Translations
   *
   * Adds translated strings for the registration flow.
   * Scoped with an IIFE to prevent global pollution. These values will be discarded once the function executes.
   * @see https://developer.mozilla.org/en-US/docs/Glossary/IIFE
   **/
  (function () {
    const phase1Translations = {
      home_ns_countdownclock_days: `Days`,
      home_ns_countdownclock_day: `Day`,
      home_ns_countdownclock_hours: `Hours`,
      home_ns_countdownclock_hour: `Hour`,
      home_ns_countdownclock_minutes: `Minutes`,
      home_ns_countdownclock_minute: `Minute`,
      home_ns_countdownclock_seconds: `Seconds`,
      home_ns_countdownclock_second: `Second`,
      home_a_herocountdown_beatpad_beats: `Beats`,
      home_a_herocountdown_beatpad_sounds: `Sounds`,
      home_a_herocountdown_beatpad_volume: `Volume`,
      home_a_herocountdown_beatpad_a: `A`,
      home_a_herocountdown_beatpad_b: `B`,
      home_a_herocountdown_beatpad_c: `C`,
      home_a_herocountdown_beatpad_min: `Min`,
      home_a_herocountdown_beatpad_max: `Max`,
      home_a_herocountdown_beatpad_off: `Off`,
      home_a_herocountdown_beatpad_1: `Beatpad 1`,
      home_a_herocountdown_beatpad_2: `Beatpad 2`,
      home_a_herocountdown_beatpad_3: `Beatpad 3`,
      home_a_herocountdown_beatpad_4: `Beatpad 4`,
      home_a_herocountdown_beatpad_5: `Beatpad 5`,
      home_a_herocountdown_beatpad_6: `Beatpad 6`,
      home_a_herocountdown_beatpad_7: `Beatpad 7`,
      home_a_herocountdown_beatpad_8: `Beatpad 8`,
      home_a_accessibility_label: `Countdown to I/O 2023`,
      home_a_herocountdown_pauseanimation: `pause animation`,
      home_a_herocountdown_playanimation: `play animation`,
      home_a_herocountdown_muteaudio: `mute audio`,
      home_a_herocountdown_playaudio: `play audio`,
      home_a_herocountdown_enterfullscreenmode: `enter full screen mode`,
      home_a_herocountdown_exitfullscreenmode: `exit full screen mode`,
      home_a_herocountdown_timeleftuntil: `Time left until I/O`,
      global_googlesign: `Sign in`,
      global_cookie_body: `This site uses cookies from Google to deliver and enhance the quality of its services and to analyze traffic.`,
      global_cookie_accept_btn: `OK, got it`,
      global_irl_inpersonenglishonly: `In-person content is available in English only `,
      community_d_newprofile_createheader_modal2_thankyou: `Thanks for creating a developer profile`,
      community_d_newprofile_createbody_modal2_nicework: `Nice work! You now have access to recommended content and can save sessions, earn badges, and more.`,
      community_d_newprofile_createctaalt_modal2_visitdevprof: `Visit your developer profile`,
      community_nd_createbody_modal1_creatingaprofile_title: `When you make a developer profile, you can save your location and get recommended events nearby.  `,
      global_nd_creatingaprofile_reccomendations: `You'll also get I/O content recommendations and can save sessions to watch after the keynote.`,
      community_nd_body_devprofile_optinlegalagreement: `By creating a Google developer profile, you agree to the [Content Policy](https://developers.google.com/profile/content-policy). [Google's Terms of Service](https://policies.google.com/terms) and [Privacy Policy](https://policies.google.com/privacy) apply to your use of this service. Your display name and location will be used in your Google Developer profile.`,
      community_d_newprofile_locationupdate: `Your location, [[ city ]], [[ state ]], has been updated to your Google developer profile.`,
      community_d_newprofile_cta1_gotit: `Got it`,
      homepagePath: `/2023/`,
      global_unabletosignin_whoops: `Whoops! Unable to sign in`,
      devprofile_learnmore_placeholder: `To learn more or get help, visit the [FAQ](/2023/about/).`,
      devprofile_useraccounttype_error: `The user account type is not allowed.`,
      global_profilecard_privacypolicy: `[Privacy Policy](https://policies.google.com/privacy)`,
      global_profilecard_terms: `[Terms of Service](http://myaccount.google.com/termsofservice)`,
      global_googlesignout: `Sign out`,
      global_profilecard_manage: `Manage your Google Account`,
      devprofile_somethingwentwrong: `Uh oh, something went wrong.`,
      nt_global_restricted_headline: `Something’s not right`,
      nt_global_restricted_copy: `It looks like you don’t have access to this page. 
`,
      nt_global_restricted_cta: `Return home`,
      nt_global_registerinpersoncomplete_headline: `Thanks for registering to attend Google I/O at Shoreline!  See you at the event on May 10.`,
      nt_global_registerinpersoncomplete_body: `Sign in to receive a badge`,
      nt_global_registerinpersoncomplete_signin_cta: `Sign in`,
      nt_language_english: `English`,
      nt_language_spanish: `Español`,
      nt_language_portugese: `Português`,
      nt_language_french: `Français`,
      nt_language_chinese: `中文`,
      nt_language_indonesian: `Indonesia`,
      nt_language_korean: `한국어`,
      nt_language_japanese: `日本語`,
      reg_filterbutton_alttext: `Filter button`,
      global_snackbar_refreshtoupdate: `New content is available. Click <b>Refresh</b> to update.`,
      global_snackbar_refresh: `Refresh`,
      nt_transpo_gettingtomountain_body2_airportcta: `[San Jose International Airport](https://www.flysanjose.com)`,
      nt_transpo_gettingtomountain_body3_airportcta: `[San Francisco International Airport](https://www.flysfo.com)`,
      nt_transpo_gettingtomountain_body4_airportcta: `[Oakland International Airport](https://www.oaklandairport.com)`,
      nt_transpo_gettingtoshoreline_publictranspo_body2: `[Caltrain Regional rail system](https://www.caltrain.com/main.html)`,
      nt_transpo_gettingtoshoreline_publictranspo_body3: `[VTA Light rail system servicing the South Bay](https://www.vta.org/)`,
      nt_transpo_gettingtoshoreline_publictranspo_body4: `[BART Bay Area Rapid Transit](https://www.bart.gov/)`,
      global_foot_svd: `I/O Puzzle`,
      global_profilecard_icon_aria: `profile icon button in the top right that opens profile card`,
      home_s_r_nd_reg_cta: `Create a developer profile`,
      home_ns_nr_reg_cta: `Register`,
      community_a_cta_seeallcomms: `[See all communities](https://developers.google.com/community)`,
      reg_a_metadatatitle_register: `Register for I/O 2023`,
      global_modals_exit_aria: `Exit`,
      reg_form_failed: `To complete registration, add in the missing required field(s)`,
      reg_conf_r_nd_requiredfield: `Required field`,
      reg_form_nr_regq_email: `Email address`,
      reg_form_nr_regq_firstname: `First Name`,
      reg_form_nr_regq_lastname: `Last Name`,
      reg_form_nr_regq_preflang: `Preferred Language`,
      reg_form_nr_rega_lang1: `English`,
      reg_form_nr_rega_lang2: `Chinese`,
      reg_form_nr_rega_lang3: `French`,
      reg_form_nr_rega_lang4: `Indonesian `,
      reg_form_nr_rega_lang5: `Japanese`,
      reg_form_nr_rega_lang6: `Korean`,
      reg_form_nr_rega_lang7: `Portuguese`,
      reg_form_nr_rega_lang8: `Spanish`,
      reg_form_nr_inclusivityconsent1: `Help make our work more inclusive for everyone.`,
      reg_form_nr_inclusivityconsent2: `We want to design programs and initiatives that drive diversity, equity, and inclusion across everything we do. The first step is getting a better understanding of the demographics of our audience. Would you like to help us by sharing some info on how you like to be represented?`,
      reg_form_nr_demographicsconsent_question: `I consent to provide Google with information about my race/ethnicity for the purposes of helping Google understand the diversity of the Google I/O audience and improve content for presentations and events.`,
      reg_form_nr_demographicsconsent_yes: `Yes, I consent
`,
      reg_form_nr_demographicsconsent_no: `No, I do not consent`,
      reg_form_nr_regq_race: `Race or ethnic identification`,
      reg_form_nr_rega_race1: `American Indian, Alaska Native, Indigenous`,
      reg_form_nr_rega_race2: `Asian or Pacific Islander`,
      reg_form_nr_rega_race3: `Black`,
      reg_form_nr_rega_race4: `Hispanic or Latino/Latina/Latinx`,
      reg_form_nr_rega_race5: `White`,
      reg_form_nr_rega_race6: `Middle Eastern`,
      reg_form_nr_rega_race7: `None of the above options apply to me`,
      reg_form_nr_rega_race8: `I do not want to disclose this information`,
      reg_form_nr_regq_prononus: `Pronouns`,
      reg_form_nr_rega_pronouns1: `She/Her`,
      reg_form_nr_rega_pronouns2: `He/Him`,
      reg_form_nr_rega_pronouns3: `They/Them`,
      reg_form_nr_rega_pronouns4: `I would select multiple options above as my pronouns`,
      reg_form_nr_rega_pronouns5: `My pronoun is not listed above`,
      reg_form_nr_rega_pronouns6: `I do not want to disclose this information`,
      reg_form_nr_regq_locationalt: `City / Town`,
      reg_form_nr_regq_optinterms: `I agree to the I/O'23 [Registration T&Cs](/2023/about/#section-five) and [Community Guidelines](https://developers.google.com/community-guidelines). I accept Google's [Terms](https://policies.google.com/terms) and acknowledge that my information will be used in accordance with Google's [Privacy Policy](https://policies.google.com/privacy).`,
      reg_form_nr_regq_18: `I am 18 years of age or older.`,
      reg_form_nr_regq_optinnews: `I would like to receive emails from Google about products and activities relevant to developers including invitations to private betas, product research, product feedback, newsletters, mentorship, and events.`,
      reg_legal_updated: `I accept Google's [Terms and Conditions](https://policies.google.com/terms) and acknowledge that my information will be used in accordance with Google's [Privacy Policy](https://policies.google.com/privacy).`,
      reg_form_nr_regq_gender: `Gender`,
      reg_form_nr_regq_genderalt2: `What is your gender?`,
      reg_form_nr_rega_gender1: `Woman`,
      reg_form_nr_rega_gender2: `Man`,
      reg_form_nr_rega_gender3: `Non-binary`,
      reg_form_nr_rega_gender4: `I do not want to disclose this information`,
      reg_legal_updated_terms: `Terms`,
      global_cookie_modals_learnmore_alt: `Learn more about google cookie policies`,
      nt_global_registerinperson_headline: `Register for I/O 2023`,
      nt_global_welcome: `You've been invited to attend Google I/O at Shoreline!  To register, please check your email.`,
      svd_a_controls_a11y_copylink: `Copy link`,
      svd_a_controls_a11y_button_copy: `Copied to clipboard`,
      global_a11y_register: `Register for Google I/O`,
      global_a11y_devprofile_signin: `Sign in to Google I/O developer profile`,
      // Create Dev Profile.
      reg_conf_r_nd_h1_thanks: `Thanks for registering!`,
      reg_conf_r_nd_h2_nextup: `Next up&#58; make your Google developer profile`,
      reg_conf_r_nd_subcopy: `Create a developer profile to get recommendations for the best I/O sessions and content for you. You can also use your profile to save and watch content  on demand.`,
      reg_createadevprofile_createprofile: `Create profile`,
      reg_createadevprofile_nothanks: `No thanks`,
      reg_createadevprofile_requiredfield: ` Required field`,
      reg_createadevprofile_createadisplayname: `Create a display name`,
      reg_createadevprofile_displayname_helptext: `Display name `,
      reg_createadevprofile_specialcharacters: `Special characters not allowed.`,
      reg_nd_legaloptin_creatingdevprofile2: `By creating a Google developer profile, you agree to the [Content Policy](https://developers.google.com/profile/content-policy). [Google’s Terms of Service](https://policies.google.com/terms) and [Privacy Policy](https://policies.google.com/privacy) apply to your use of this service. Your display name, organization, role, and interests will be used in your profile, along with the location entered in registration. Your display name may appear where you contribute and can be changed at any time.

`,
      reg_nd_legaloptin_creatingdevprofile_alt: `By creating a Google developer profile, you agree to the [Content Policy](https://developers.google.com/profile/content-policy). [Google’s Terms of Service](https://policies.google.com/terms) and [Privacy Policy](https://policies.google.com/privacy) apply to your use of this service. Your display name, organization, role, and interests will be used in your profile. Your display name may appear where you contribute and can be changed at any time.`,
      reg_d_legaloptin_updateprofile_interests2: `By selecting “Update Profile,” you agree to update the following on your Google developer profile&#58;
<ul><li>Location</li>
<li>Interests</li></ul>
If your profile privacy is currently set to public, this information will also be public.`,
      reg_d_legaloptin_updateprofile_interests2alt: `By selecting “Update Profile,” you agree to update the following on your Google Developer profile:
<ul><li>Location</li>
<li>Organization</li>
<li>Role</li>
<li>Interests</li></ul>
If your profile privacy is currently set to public, this information will also be public.`,
      reg_d_legaloptin_updateprofile_interests: `By selecting “Update Profile,” you agree to update the following on your Google developer profile&#58;
<ul><li>Interests</li>
<li>Organization</li>
<li>Role</li></ul>
If your profile privacy is currently set to public, this information will also be public.`,
      reg_d_legaloptin_profilepublic_changes: `You can make changes to your developer profile at any time <a href='https://developers.google.com/profile/u/me/' target='_blank' aria-label='Developer profile, opens in a new tab' class="cta-link-btn">here</a>.`,
      reg_conf_r_nd_selectinterests: `Select your interests`,
      reg_form_nr_regq_organization: `Company, organization, education institution, or publication`,
      reg_form_nr_regq_role: `Role, practitioner, or job title `,
      reg_form_nr_rega_role1: `Architect`,
      reg_form_nr_rega_role2: `Data Analyst`,
      reg_form_nr_rega_role3: `Data Engineer`,
      reg_form_nr_rega_role4: `Data Scientist`,
      reg_form_nr_rega_role5: `Designer`,
      reg_form_nr_rega_role7: `Developer`,
      reg_form_nr_rega_role8: `Developer Advocate`,
      reg_form_nr_rega_role9: `Educator`,
      reg_form_nr_rega_role12: `Machine Learning Engineer`,
      reg_form_nr_rega_role13: `Network Engineer`,
      reg_form_nr_rega_role14: `Product Manager`,
      reg_form_nr_rega_role15: `Security Professional`,
      reg_form_nr_rega_role16: `Something Else`,
      reg_form_nr_rega_role17: `Student`,
      reg_form_nr_rega_role18: `SysAdmin`,
      reg_form_nr_rega_role19: `Technical Writer`,
      reg_form_nr_rega_role20: `I do not want to disclose this information`,
      reg_form_nr_rega_role_database: `Database Admin`,
      reg_nd_legaloptin_createprofilechanges: `If you choose to create a profile, you can make changes to it <a href='https://developers.google.com/profile/u/me/' target='_blank' aria-label='Developer profile, opens in a new tab'>here</a>.`,
      reg_conf_r_nd_optin_stayup: `I would like to receive emails regarding new features, events, badges, content, and research opportunities.`,
      global_opennewtab_aria: `open in new tab`,
      // Update Dev Profile.
      reg_conf_r_nd_h2_nextup_update: `Next up&#58; update your Google developer profile`,
      reg_conf_r_d_subcopy: `Share what you want to learn about to get recommendations for the best I/O sessions and content for you. You can also use your developer profile to save sessions to watch after the keynote.`,
      reg_updateadevprofile_updateprofile: `Update profile`,
      global_createadevprofile: `Create a Google developer profile`,
      global_register: `Register`,
      devprofile_r_d_h1_updatedevprofile: `Update your Google developer profile`,
      reg_devprofile_updated_aria: `Developer profile updated`,
      reg_devprofile_created_aria: `Developer profile created`,
      // Badge Modal
      reg_success_r_d_b_h1_seeyou: `See you at Google I/O, [[ name ]]!`,
      reg_success_r_d_b_h2_earnedbadge: `You earned a badge! `,
      reg_success_r_d_b_h2_attendee: `I/O 2023 Attendee`,
      reg_success_r_d_b_body_badgesaved: `This badge was saved to your developer profile.`,
      reg_success_r_d_b_badgecta_share: `Share your badge `,
      reg_success_r_d_b_alt_orgodevprofile: `or go to your <a href="https://developers.google.com/profile/u/me" target="_blank" class="cta-link-btn" rel="noopener">developer profile</a>`,
      reg_success_r_d_b_h2_badge_2023: `I/O 2023
Attendee
May 10, 2023`,
      reg_success_r_d_b_alt_share: `Links to share on Facebook, Twitter, LinkedIn, or elsewhere`,
      svd_a_controls_a11y_share_tw: `Share to Twitter`,
      svd_a_controls_a11y_share_li: `Share to LinkedIn`,
      // No Thanks Modal
      reg_success_nd_nb_body_thankyou: `Thank you for registering.`,
      // Community
      community_ns_searchbar_searchforcity: `Enter your city/town`,
      community_a_locationgroup_alt3_joinchapter: `Join chapter`,
      community_a_f2_cta_findstudentclub: `[Find a Google Developer Student Club](https://developers.google.com/community/gdsc)`,
      community_a_f3_cta_findgoogledevgroup: `[Find a Google Developer Group](https://developers.google.com/community/gdg)`,
      community_a_f1_cta_join: `[Join Google's Women Techmakers](https://www.womentechmakers.com/members)`,
      global_cookie_modals_learnmore: `[Learn more](https://policies.google.com/technologies/cookies)`,
      community_d_newprofile_savelocation_modal3_body_nearbyevents: `Can we save your location in your Google developer profile? We'll use this to recommend nearby events.`,
      reg_conf_r_nd_isrequiredfield: `is required`,
      community_d_newprofile_savelocation_modal3_savelocation: `Save your location`,
      community_d_body_devprofile_updateprofileandsavelocation: `By selecting “Update profile,” you agree to update your location on your Google developer profile. If your profile privacy is currently set to public, this information will also be public.`,
      reg_form_nr_regq_location_error: `No groups found in your area.`,
      community_d_newprofile_successsaved: `Location saved!`,
      global_opennewwindow_aria: `open in new window`,
      global_unabletosignin_devprofile: `A Google developer profile allows you to save your interests, documentation, and pathway progress in one place. During I/O, a developer profile will allow you to get custom recommendations and save sessions and learning material in My I/O.`,
      global_unabletosignin_toregister: `To register, grant permission to view, edit, and create your Google developer profile.`,
      gloval_unabletosignin_tryagain: `Try again`,
      reg_conf_r_nd_createdisplay: `Create a display name`,
      reg_form_error_ageverification: `Age verification is required`,
      reg_form_error_terms: `Acceptance of terms and conditions is required`,
      home_a_herocountdown_volume_1: `Volume 1`,
      home_a_herocountdown_volume_2: `Volume 2`,
      home_a_herocountdown_volume_3: `Volume 3`,
      home_a_herocountdown_volume_4: `Volume 4`,
      home_a_herocountdown_volume_5: `Volume 5`,
      home_a_herocountdown_volume_6: `Volume 6`,
      home_a_herocountdown_volume_7: `Volume 7`,
      home_a_herocountdown_volume_8: `Volume 8`,
      home_a_herocountdown_volume_9: `Volume 9`,
      home_a_herocountdown_volume_10: `Volume 10`,
      home_a_herocountdown_volume_11: `Volume 11`,
      home_a_accessibility_closepanel: `Close control panel`,
      home_a_accessibility_openpanel: `Open control panel`,
      global_a_filters_results: `Results`,
      community_a11y_groups: `group(s) found near your location`,
      nt_inpersonbanner_copyalt: `Google I/O is back on May 10,  live from Shoreline in Mountain View, CA`,
    };
    const original =
      typeof window.translations !== "undefined" ? window.translations : {};

    // Add Reg Flow Translations To Window.
    window.translations = Object.assign(original, phase1Translations);
    return;
  })();
</script>
  
  <script defer>
  /**
   * Phase2 Translations
   *
   * Adds translated strings for the registration flow.
   * Scoped with an IIFE to prevent global pollution. These values will be discarded once the function executes.
   * @see https://developer.mozilla.org/en-US/docs/Glossary/IIFE
   **/
  (function () {
    const phase2Translations = {
      watch_a_filter1: `Focus`,
      watch_a_filter2: `Topics`,
      watch_a_filter3: `Content type`,
      watch_a_filter4: `Level`,
      watch_a_filter1_cat1: `Mobile`,
      watch_a_filter1_cat2: `Web`,
      watch_a_filter1_cat3: `AI`,
      watch_a_filter1_cat4: `Cloud`,
      global_a_filter_level_beginner: `Beginner`,
      global_a_filter_level_intermediate: `Intermediate`,
      global_a_filter_level_advanced: `Advanced`,
      global_a_more: `More`,
      global_a_less: `Less`,
      program_showless_topics: `Show less topics`,
      program_showmore_topics: `Show more topics`,
      global_filteralt_remove: `remove filter for`,
      reg_filterbutton_alttext: `Filter button`,
      global_filteralt_menu: `filter menu`,
      global_a_filters_clearall: `Clear all`,
      global_aria_late_filterremoved: `Filter [[ filter ]] has been removed`,
      watch_a_filter3_cat1: `Keynote`,
      watch_a_filter3_cat2: `Technical session`,
      watch_a_filter3_cat3: `Workshop`,
      watch_a_filter3_cat4: `Codelab`,
      watch_a_filter3_cat5: `Learning pathway`,
      watch_a_filter3_cat6: `Demo`,
      reg_conf_r_nd_interest18: `Smart Home`,
      global_s_myio: `My I/O`,
      community_connnect_cta: `[Find an event](https://developers.google.com/events)`,
      community_extended_cta: `[Find an event](https://gdg.community.dev/ioextended/)`,
      myio_close_myio: `Close My I/O`,
      myio_io_settings: `Profile Settings`,
      watch_a_butterbar: `I/O content will be available on demand after the keynotes`,
      home_a_cal_headline: `Add to your calendar `,
      addtocal_google: `Google calendar`,
      addtocal_outlook: `Outlook calendar`,
      addtocal_apple: `Apple calendar`,
      home_s_r_d_keynote1_button1: `Save to My I/O`,
      svd_a_info_a11y_dark: `Dark mode`,
      svd_a_info_a11y_light: `Light mode`,
      watch_a_a11y_addbookmark: `Bookmark this session`,
      watch_a_a11y_removebookmark: `Remove bookmark`,
      home_a_keynote1_button1: `Add to calendar`,
      svd_a_info_a11y_on: `On`,
      nt_transpo_gettingtoshoreline_publictranspo_body4b: `[MVgo](https://mvgo.org/routes/b/)`,
      community_a_viewallcontent: `[View all content](/2023/program/)`,
      home_a_viewallcontent_a11y: `View all Google I/O Content`,
      global_refreshbrowser_copy1: `Refresh your browser to catch the latest during I/O 2023!`,
      global_refreshbrowser_copy2: `Google I/O is happening now. Tune in to catch the latest!`,
      global_refreshbrowser_cta1: `Refresh`,
      community_a_learningmodule_cta: `[Browse topics](/2023/learn/)`,
      watch_a_a11y_aroundgoogletech: `Browse topics around Google technology`,
      home_a_connect_cta_a11y: `Find an I/O Connect event`,
      home_a_extended_cta_a11y: `I/O Extended events in your area`,
      "home_a_about_cta": `[Learn about I/O](/2023/about/)`
    };
    const original =
      typeof window.translations !== "undefined" ? window.translations : {};

    // Add Reg Flow Translations To Window.
    window.translations = Object.assign(original, phase2Translations);
    return;
  })();
</script>
  
  <script defer>
  /**
   * Phase3 Translations
   *
   * Adds translated strings for the registration flow.
   * Scoped with an IIFE to prevent global pollution. These values will be discarded once the function executes.
   * @see https://developer.mozilla.org/en-US/docs/Glossary/IIFE
   **/
  (function () {
    const phase3Translations = {
      "home_a_3.1_header": `Google keynote is live `,
      "home_a_keynote_videohero_cta_watchkeynote": `Watch the livestream`,
      "home_a_keynote_videohero_cta_watchwithasl3.1": `Watch with an ASL interpreter`,
      "global_a_watchandexplore": `[Watch and explore](/2023/program/)`,
      "about_a_adventurechat_cta": `<a href="https://adventure.withgoogle.com/io/" target="_blank" class="cta-link-btn" rel="noopener">Join the conversation</a>`,
      "about_a_adventurechat_cta_a11y": `Opens I/O Adventure chat page`,
      "about_a_learning_cta": `[Start learning](/2023/learn/)`,
      "about_a_learning_cta_a11y": `Opens learning material on watch and explore page`,
      "home_a_adventure_cta": `[Join the conversation](https://adventure.withgoogle.com/io/)`,
      "home_a_adventurehero_body_joinchat3_alt": `Ask questions and connect with the community in I/O Adventure Chat.`,
      "home_a_keynote_videohero_livestream_a11y": `Watch the I/O 2023 livestream`
    };
    const original =
      typeof window.translations !== "undefined" ? window.translations : {};

    // Add Reg Flow Translations To Window.
    window.translations = Object.assign(original, phase3Translations);
    return;
  })();
</script>
  
  <script defer>
  /**
   * Phase4 Translations
   *
   * Adds translated strings for the registration flow.
   * Scoped with an IIFE to prevent global pollution. These values will be discarded once the function executes.
   * @see https://developer.mozilla.org/en-US/docs/Glossary/IIFE
   **/
  (function () {
    const phase4Translations = {};
    const original =
      typeof window.translations !== "undefined" ? window.translations : {};

    // Add Reg Flow Translations To Window.
    window.translations = Object.assign(original, phase4Translations);
    return;
  })();
</script>
  
  
    
  
  <script src="https://apis.google.com/js/platform.js"></script>
  
  <script src="/2023/app/iofe_vendors.chunk.71410d9eaed8e41b3d81.js"></script>
  <script src="/2023/app/iofe_bundle.6aa9e910050e0ff94783.js"></script>
  <script src="/2023/app/iofe_polyfills.018ee674f227e6850b02.js"></script>
  
  <script src="/2023/app/js/developer_profiles_api_v2.js"></script>
  
</body>
</html>
