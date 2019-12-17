# slurpee-wedding-pizza

## TODO

- [x] background GIF
- [x] click MP3
- [x] BG MIDI song
- [x] snowing image
- [ ] titles
- [x] title tag - get hitched, yo
- [ ] memes
- [ ] actual info
- [x] embed eventbrite page
- [ ] low quality jpgs of us
- [ ] put it in an HTML file
- [ ] upload it all


RSVP Code:
```
<!-- Noscript content for added SEO -->
<noscript><a href="https://www.eventbrite.ca/e/et-wedding-tickets-86465200743" rel="noopener noreferrer" target="_blank"></noscript>
<button id="eventbrite-widget-modal-trigger-86465200743" type="button">RSVP Online!</button>
<noscript></a>RSVP Online!</noscript>

<div id="eventbrite-widget-container-86465200743"></div>

<script src="https://www.eventbrite.ca/static/widgets/eb_widgets.js"></script>
<script type="text/javascript">
    var exampleCallback = function() {
        console.log('Order complete!');
    };

    window.EBWidgets.createWidget({
        widgetType: 'checkout',
        eventId: '86465200743',
        modal: true,
        modalTriggerElementId: 'eventbrite-widget-modal-trigger-86465200743',
        onOrderComplete: exampleCallback
    });
    window.EBWidgets.createWidget({
        // Required
        widgetType: 'checkout',
        eventId: '86465200743',
        iframeContainerId: 'eventbrite-widget-container-86465200743',

        // Optional
        iframeContainerHeight: 425,  // Widget height in pixels. Defaults to a minimum of 425px if not provided
        onOrderComplete: exampleCallback  // Method called when an order has successfully completed
    });
</script>
```
