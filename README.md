# H5P.Anki (IDEA)

You choose a content type among a list of supported content type and it diplay a button, if you click on it it add cards to anki based on the content type

## Supported content type

- Dialog Card ⭐⭐⭐
- Flash cards ⭐⭐⭐
- Image pairing ⭐
- Memory game ⭐
- Multiple choice ⭐⭐
- Single choice set ⭐⭐
- True / false ⭐
- Anki (just offer to download)

## Two possibility

Either the cards are added to anki with the anki connect api, this require the user to install the plugin, and configure it to give api access.
Or the anki connect api is used in the authoring view to generate a anki file that can be then simply downloaded by student

If anki connect is student side, a possibility would also be to add an option to allow to open add preffilled add card popup so the student can modify before adding.

But I think I will go with the authoring view side.

## Option

The button to download can be set to be displayed at the start, or on activity completion
