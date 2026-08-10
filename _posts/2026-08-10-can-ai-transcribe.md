---
title: "Can AI transcribe 17th century documents?"
excerpt: "Generative AI assistants are everywhere, and it seems like they're here to stay. You know the ones—ChatGPT, CoPilot, Claude and Gemini..."
layout: single
---

Generative AI assistants are everywhere, and it seems like they're here to
stay. You know the ones---ChatGPT, CoPilot, Claude and Gemini. AI assistants
have also been carving a space for themselves in the world of genealogy and 
have---apparently---"fundamentally transformed" the way
family history is being done. According to AI, transcription is where these
tools are really shaking things up, though, with these assistants
"exceptionally good at interpretating" difficult to read handwriting. 

So, just how good are these assistants at transcribing and should we be using
them? 

To start answering these questions, I put ChatGPT to the test with a 1635
memorandum made by trustees of a charity outlining rent due by their tenant, Mr
Sugar:

<figure class="align-center">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/2026_08_10_can_ai_transcribe/transcription_text.jpg" alt="17th century handwriting for transcription">
</figure> 
This is exactly the type of text you would want transcribing automatically.
Firstly, the handwriting is fairly challenging to read---it has lots of
abbreviations and some overlapping text, so it could potentially take a while
to decipher. Secondly, it is also very repetitive, and the same words are used
again and again---just the type of mundane text you might want AI to transcribe
for you.

I kept the prompts simple. I asked ChatGPT to pretend they were a genealogist
and asked it to transcribe the document. At an initial glance, the results were
promising. It started with a summary of the document where it identified the
document type ("a legal or estate document"), and it had roughly identified the
correct date (1630--40). It had also pointed out it was filled with many
abbreviations (ye = "the", yt = "that" etc) and highlighted any archaic
language ("messuage"). So far, so good. 

Next, it produced the transcript. Again, on the surface, the results looked
positive: the majority of the text had been transcribed and there were very few
gaps where words couldn't be identified. It had picked out some of the key
words (such as the tenant's name, Sugar), and the numbers had largely been
identified. If I didn't know better, I would have assumed that this was a
decent transcript. 

Fortunately, though, I do know better, and it was surprising just how wrong AI
had got it. I'm not just talking one or two words were mistranscribed---no,
I'm talking about 90% of the text being completely wrong/made up, to the point
where I had to go back and check if I'd uploaded a different document by
mistake.

The inability to unpack abbreviations is probably one of its biggest struggles,
with abbreviated words like "or" (our) ignored or wrongly transcribed. It also
struggled with transcribing place names. In this instance, Whaplode Drove
(Lincolnshire) was not identified, and I can't even work out what it was
transcribed as instead as the sentences don't follow the same structure as the
original. Further, it has a habit of assuming all numbers relate to a date: £5
15s becomes 5th--25th, with neither the numbers or currency correctly
identified.

However, it is its complete failing at deciphering any of the words which
renders it virtually useless. Take the first sentence. AI had transcribed it as
follows:

> "The said Sugar aforesd shall dure for soe of ye remainder of"

But here's what it actually says:

> "Md ye ffeoffees of the Almeshouse of ye foundac[i]on of Mr Willesby in considerac[i]on"

Not a single word is correct, unless we're counting "the" at the start of the
sentence (although it did ignore md---an abbreviation of memorandum). The rest
of the text is similar---a couple of key words picked out and the rest made up.
It has picked up that it's about land and there's a tenant involved, and money
is due at some point, but the rest is all being guessed based on the keywords 
identified.

If I refined the prompts and gave it more detail, then maybe it would have had
produced a better output. For instance, I could have told it it was a tenancy
agreement for the renting of charity land, with the profits going towards the
maintenance of the town poor, and I might have got a more accurate
transcription. Yet sometimes you might not have that level of detail until
you've actually transcribed the document!

The genuinely worrying thing about this output, though, is how convincing it
reads as a legitimate transcription. It has all of the right words ("tenement",
"lease", "land" and "messuage") to make you think it knows what it's doing, and
the words it uses to string them together are also convincing. For instance,
this could read as a perfectly legitimate sentence:

> "in respect thereof ye said lease aforesd and land"
 
and you could be forgiven for thinking it was a reliable, coherent transcription.
Unfortunately, though, it is completely made up and not even close to the original:

> "W[hi]ch we purchased in Whaplode drove for ye use"

Maybe in a few years, the technology will have developed, and AI assistants
will be far more powerful tools in transcription. For now, however, we need to
be aware of the dangers of relying on generative AI for transcriptions and
never take its output at face-value. Unless you can verify what it is telling
you---either by transcribing it yourself or getting someone to help---take it
with a pinch (or spoonful) of salt, otherwise it may well be telling you a load
of nonsense.