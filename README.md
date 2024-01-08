
<html>
  <body>

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D2w000006Z8pr',
				'Messagining_in_App_Web',
				'https://hostpapa.my.site.com/ESWMessagininginAppWeb1703832885217',
				{
					scrt2URL: 'https://hostpapa.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://hostpapa.my.site.com/ESWMessagininginAppWeb1703832885217/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
