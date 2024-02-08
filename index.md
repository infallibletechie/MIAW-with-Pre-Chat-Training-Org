<html>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHo000002fRR9',
				'MIAW_with_Pre_Chat',
				'https://infallibletechie2-dev-ed.develop.my.site.com/ESWMIAWwithPreChat1707421776301',
				{
					scrt2URL: 'https://infallibletechie2-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://infallibletechie2-dev-ed.develop.my.site.com/ESWMIAWwithPreChat1707421776301/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
