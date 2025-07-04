# My Strudel Samples

A small collection of audio samples I use in my Strudel patterns. Nothing fancy, just stuff that sounds good when chopped up and processed.

## What's In Here

- **heartbeat/** - Stolen sample from DJDave for learning
- **nanou2/** - Aphex twin sample
- More stuff as I add it

## Using These Samples

```javascript
// Load the samples
samples("github:oscarbeamish/samples")

// Use them in patterns
s("heartbeat:0").slow(2)
s("heartbeat:1").chop(8).rev()
```

The `strudel.json` file tells Strudel where everything is:

```json
{
  "_base": "https://raw.githubusercontent.com/oscarbeamish/samples/main/",
  "heartbeat": ["heartbeat/heartbeat1.wav", "heartbeat/heartbeat2.wav"],
  "nanou2": ["nanou2/intro.wav"]
}
```

## Sample Processing Ideas

The heartbeat samples work well with:

```javascript
s("heartbeat:0")
  .slice(8, "0 3 2 7") // Chop it up
  .speed("<0.5 1 2>") // Vary speed
  .lpf(1000) // Filter

s("heartbeat:1")
  .chop(32) // Granular
  .room(0.8) // Spacey
```

## File Formats

- WAV files, usually 16 or 24-bit
- Sample rate doesn't matter much, Strudel handles it
- Lengths vary - some are loops, some are one-shots

## Adding New Samples

1. Put the audio file in the right folder
2. Update `strudel.json` with the path
3. Test it works in Strudel

Pretty straightforward. Keep file sizes reasonable since they load over the web.

## License

Do whatever you want with these. If you make something cool, let me know, but no obligation.
