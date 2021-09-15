# splunk-config-editor
A web based configuration editor for Splunk and Splunk Cloud

This is a completely local browser-based application, which means you have browser security to consider. The domain the page is served from will need to be accepted by the `crossOriginSharingPolicy` setting, and the Splunk server you connect to will need to serve a valid SSL certificate on its 8089 splunkd port.
