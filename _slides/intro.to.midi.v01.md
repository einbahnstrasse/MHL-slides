  <!-- Intro to MIDI | Intro to Digital Music        -->

Intro to MIDI Intro to MIDI

##### Introduction to Digital Music — Louis Goldford (2023)

##### These slides will discuss:

##### These slides will discuss:

###### What is MIDI?

###### Software + Hardware

###### The MIDI Technical Standard

###### MIDI For the Future

##### These slides will discuss:

###### What is MIDI?

*   MIDI Definition + Use Cases
*   MIDI History

###### Software + Hardware

*   Cables, Connectors, and MIDI Controllers
*   Using MIDI in a Sequencer

###### The MIDI Technical Standard

*   "Note-On," "Note-Off," and Other Messages
*   Program Change + Control Change Messages
*   MIDI File Formats + Sound Banks

###### MIDI For the Future

*   Expressive New MIDI Controllers
*   MPE (MIDI Polyphonic Expression)
*   MIDI Over USB, TRS, Ethernet, Wireless

#### What is MIDI? — MIDI Definition + Use Cases

#### What is MIDI? — MIDI Definition + Use Cases

**Musical Instrument Digital Interface** (MIDI) is a technical standard that allows multiple electronic devices to **synchronize** data in real-time.

#### What is MIDI? — MIDI Definition + Use Cases

**Musical Instrument Digital Interface** (MIDI) is a technical standard that allows multiple electronic devices to **synchronize** data in real-time.

These could be **synthesizers** playing the same notes and rhythms...

#### What is MIDI? — MIDI Definition + Use Cases

**Musical Instrument Digital Interface** (MIDI) is a technical standard that allows multiple electronic devices to **synchronize** data in real-time.

These could be **synthesizers** playing the same notes and rhythms...

Or **faders on a mixer** that move up and down on their own,  
controlled by computer software...

#### What is MIDI? — MIDI Definition + Use Cases

**Musical Instrument Digital Interface** (MIDI) is a technical standard that allows multiple electronic devices to **synchronize** data in real-time.

These could be **synthesizers** playing the same notes and rhythms...

Or **faders on a mixer** that move up and down on their own,  
controlled by computer software...

Or **lights** that blink in time with music.

#### What is MIDI? — MIDI Definition + Use Cases

In other words, MIDI connects all of these devices:

#### What is MIDI? — MIDI Definition + Use Cases

MIDI allows all of these devices to share the same **event data**:

**Events** (like notes) are triggered on all devices **at the same time**.

#### What is MIDI? — MIDI Definition + Use Cases

###### Use Cases — What is MIDI Used For?

*   Realtime **synchronization** of musical playback on digital instruments, such as keyboards, samplers, and [Disklaviers](https://youtu.be/BswLMDavu80?t=86)
*   **Controlling** analog instruments, such as [Eurorack modular synthesizers](https://youtu.be/b0p9rH8K3uY?t=57)
*   **Synchronizing** [lighting networks](https://youtu.be/ybVoFn04Y94?t=332)
*   Offline **sequencing** musical notes and rhythms in a musical work
*   **Editing** a note's paramters: rhythm, duration, pitch, loudness, or timbre
*   **Controlling** virtual musical instruments, like plug-ins and VSTs
*   **Storing** a musical score in a small file format

#### What is MIDI? — MIDI Definition + Use Cases

###### Use Cases — What is MIDI Used For?

##### Note: Realtime vs. Offline

**Realtime**: _synchronous_, instantly rendered within a  
fraction of a second in **performance**

**Offline**: _not synchronous_, rendered later,  
after careful editing, in a **composition**

#### What is MIDI? — MIDI Definition + Use Cases

###### Are MIDI and sound the same thing?

Good question, but... **NO!**

Sound signals represent pressure waves travelling through air.

Sound can be stored in a **digital or analog medium**

such as CDs or magnetic tape.

MIDI is a **digital** format, but **does not  
transmit recorded sound** and is not a signal.

#### What is MIDI? — MIDI Definition + Use Cases

###### MIDI is like a musical score...

It can store very **accurate timing information**

about musical parameters like  
**pitch**, **rhythm**, **duration**, **tempo**, and **timbre**.

MIDI can be stored in **small files:**  
ca. 1000 times less space than audio files!

Like **musical scores**, MIDI can be stored in simple **text files**.

_MIDI is a very **efficient** way of  
storing **musical instructions** on a computer._

#### What is MIDI? — MIDI Definition + Use Cases

###### Is MIDI a computer language?

Good question, but... **NO!**

Computer languages allow you to construct **systems of logic**,

and include many **classes** (i.e., data types),

which can process everything from numbers to letters to sound files.

MIDI, however, is far more basic than that...

#### What is MIDI? — MIDI Definition + Use Cases

###### Is MIDI a computer language?

MIDI **only stores numbers**.

These numbers do not represent sound,  
but only event **triggers**.

MIDI cannot represent any other type of data  
and only performs one simple task:

#### What is MIDI? — MIDI Definition + Use Cases

###### Is MIDI a computer language?

MIDI sends **binary messages** that are **interpreted**  
exactly at the moment they are sent and received...

So, when you depress a key on the keyboard,

or move a fader on the mixer,

**instantly** a sound is produced,

or a light switches on!

#### What is MIDI? — MIDI Definition + Use Cases

###### Is MIDI a computer language?

MIDI is therefore **_not_** a computer language

and is best thought of as a simple  
**control protocol**.

#### What is MIDI? — History — The 1960s

These synthesis pioneers did not use MIDI.

Before MIDI, cables transported **control voltage**,

delivering **electricity** as a sole means  
of controlling sonic events.

###### Don Buchla

###### Bob Moog

#### What is MIDI? — History — The 1970s

###### 1970s synths

**Many companies** designed their own synths,

but these instruments could not communicate...

**Korg** and **Yamaha** used one connection format,

but **Moog** and **Roland** used another.

#### What is MIDI? — History — 1981

In 1981, Dave Smith of **Sequential Circuit** developed  
a **message** to send **pitch data** at a 19600 baud rate.

Ikutaro Kakehashi of **Roland** also worked on a **common language**  
for synthesizers shared by **Yamaha**, **Korg**, and **Akai**.

**Roland** and **Korg** began discussing the need for a **standard** for all  
synthesizers at **AES** ("Audio Engineering Society") in California.

#### What is MIDI? — History — 1982

###### Sequential Circuit Prophet 600 and Roland Jupiter 6 (1982)

By 1982, the first MIDI-compliant synthesizers were born.

#### What is MIDI? — History — 1982

In 1982, the first **technical specification** was published on the MIDI standard:

*   MIDI messages included: **Note-On** and **Note-Off**, **Pitch Bend**, **Control Change**, **Aftertouch**, and **SysEx**.
*   A standard 5-pin MIDI cable and port
*   IN, OUT, and THRU connections among synthesizers
*   Transmission of up to 16 channels per port
*   Baud rate of 31250
*   Establishment of the **IMA** (International MIDI Association) to coordinate future work on the standard

#### What is MIDI? — History — Early Computer MIDI

The first **computer and software implementations** of MIDI were born.

#### Software + Hardware — Cables, Connectors, and MIDI Controllers

MIDI messages were first transmitted on **5-pin DIN** cables...

#### Software + Hardware — Cables, Connectors, and MIDI Controllers

...which connected a synthesizer's **IN**, **OUT**, and **THRU** ports:

*   **IN** receives MIDI messages.
*   **OUT** sends MIDI messages.
*   **THRU** passes messages received by **IN**.

#### Software + Hardware — Cables, Connectors, and MIDI Controllers

With MIDI **THRU** it is possible to connect several synths in a "daisy chain"

and to control them all from one device (e.g., Instrument 1 above).

#### Software + Hardware — Cables, Connectors, and MIDI Controllers

But there were several problems with this **chain configuration**:

*   16 channels must be **shared among all connected instruments**.
*   **Latency** occurred at the end of the chain (e.g., Instrument 4).
*   Messages could only be sent _to_ the synths but not _from_ them.  
    Yet, both directions are necessary for **computer sequencing**.

#### Software + Hardware — Cables, Connectors, and MIDI Controllers

A solution is the **star configuration**.

*   One **"master"** computer controls any number of **"slaves."**
*   No **Latency** because of shorter connections.
*   Each **slave** shares its own 16 channels over a unique physical connection.
*   Notice the **MIDI interface** and **USB connection** in the center of the "star."

#### Software + Hardware — Using MIDI in a Sequencer

Here, sequencer software (Ableton Live) **records** and **plays back** MIDI data.

MIDI "clips" store this data in a [piano roll editor](https://www.ableton.com/en/manual/editing-midi-notes-and-velocities/) (bottom of screen).

The **sequencer** makes no sound by itself;  
it only **triggers** notes played by software synthesizers.

#### Software + Hardware — Using MIDI in a Sequencer

The **keyboard** he plays functions as a **MIDI Controller**:

it **controls** the playback of another MIDI device, like the software synth.

After recording the MIDI information, the **sequencer** acts as a **controller**  
when it plays the software synth!

#### Software + Hardware — Using MIDI in a Sequencer

Here, another sequencer (Apple Logic) **controls**  
2 other **peripherals**: the Korg NS5R and X5DR samplers.

Sound **samples** are stored in the Korg periphals

while the **sequencer** (Logic) again makes no sound by itself;  
the software only **triggers** notes on the peripherals.

#### MIDI Technical Standard — Encoding

###### So... Where does this mad science come from?!

#### MIDI Technical Standard — Encoding

###### Each MIDI message includes 2 components:

*   a **Status Byte**: Defines the message type and the channel number.
*   and (a) **Data Byte(s)**: Binary numbers formatted for each type of message.

#### MIDI Technical Standard — Encoding

###### All message components are sent in binary.

Binary: **lists** containing only digits 0 or 1,  
which represent a number or letter

_next slide:_ how to convert a  
base 10 number to a binary number...

#### MIDI Technical Standard — Encoding

Decimal to Binary Converter

[![Inch Calculator Logo](https://cdn.inchcalculator.com/e/inch-calculator-logo-tiny.png)Inch Calculator](https://www.inchcalculator.com/decimal-to-binary-converter/)

#### MIDI Technical Standard — Encoding

###### Status Byte

Defines the message type and the channel number.

*   **1 bit**
*   **3 bits**: message type
*   **4 bits**: MIDI channel number (0-15)

#### MIDI Technical Standard — Encoding

###### Types of Messages (3 bits):

binary

message type

description

000

**Note-Off**

release a note

001

**Note-On**

start a note

011

**Control Change**

change continuous controller

100

**Program Change**

change sound

101

**Aftertouch**

global pressure per channel

010

**Polyphonic Aftertouch**

pressure for each key

110

**Pitch Bend**

glissando around a pitch value

#### MIDI Technical Standard — Encoding

###### Data Bytes

Includes the data formatted for each type of message.

A **data byte** is 7 binary digits, which can represent  
numbers ranging from 0 to 127.

The number of data bytes following a status  
byte depends on the type of message sent.

#### MIDI Technical Standard — Encoding

###### Examples of Data Bytes

#### MIDI Technical Standard — Encoding

###### Note-On and Note-Off Messages

Notice that these messages _(previous slide)_ require **2 data bytes**:

One number represents **pitch** while the other represents **velocity**, or **loudness**.

**Pitch** values (0-127) span the range of the orchestra.  
MIDI note number 60 is middle C.

**Velocity** values also range from 0 (silent) to 127 (loudest possible sound).

A velocity value of 0 is considered a **Note-Off** message.

#### MIDI Technical Standard — Encoding

###### Note-On and Note-Off Messages

All "notes," then, require 2 MIDI messages:

*   a **Note-On** message, which sends the note's **pitch** and **velocity**,  
    and which also **"starts"** the note, and
*   a **Note-Off** message, which **"turns off"** the corresponding note  
    after it is "held" for some **duration**.

#### MIDI Technical Standard — Encoding

Here is a single note in a **piano roll sequencer**.

The playhead, moving from left to right, first rolls over **point A**,  
which triggers the **Note-On** message:

10010001 0111100 1100100 meaning:

status byte + type: Note-On + channel: 1 + MIDI note: 60 + Velocity: 100

#### MIDI Technical Standard — Encoding

After some **duration** (length of the blue bar), the playhead rolls over **point B**,  
which triggers the **Note-Off** message:

10000001 0111100 0000000 meaning:

status byte + type: Note-Off + channel: 1 + MIDI note: 60 + Velocity: 0 (silence!)

#### MIDI Technical Standard — Encoding

###### MIDI File (.mid) Formats

Musical scores can be represented as MIDI files in 2 ways:

*   **Format 0:** All MIDI data is reduced to a **single track**,  
    but parsed by channel number in each MIDI message.
*   **Format 1:** Each channel is represented as a separate track; useful for **sequencers**, where each instrument is placed on a separate track.

#### MIDI Technical Standard — Encoding

###### MIDI File (.mid) Formats

**.mid** files can be opened by many **music notation programs**

like **Finale**, **Sibelius**, **MuseScore**, **LilyPond**, or **Dorico**.

#### MIDI Technical Standard — Encoding

###### [General MIDI:](https://de.wikipedia.org/wiki/General_MIDI) A Standard Sound Bank

A bank of sounds used by all synthesizers,  
including software synthesizers available on computers.

Users can call the same instrument represented by a  
**program change number** on any MIDI-compatible instrument.

#### MIDI Technical Standard — Encoding

###### [General MIDI:](https://de.wikipedia.org/wiki/General_MIDI) A Standard Sound Bank

Here, all 128 General MIDI **programs** are played, one at a time on the same pitch, using the internal synth that comes installed on Windows computers.

#### MIDI For the Future — Expressive New MIDI Controllers

The TouchMe MIDI controller uses the **electrical resistance**  
of connected objects to send MIDI messages.

#### MIDI For the Future — Expressive New MIDI Controllers

The Roli Seaboard controllers allow for **continuous change**  
in pitch, timbre, and other synthesis parameters.

#### MIDI For the Future — Expressive New MIDI Controllers

The Karlax controller uses **gyroscope sensors**  
to generate **gesture data** and can be performed by  
a musician or a dancer, for example.

#### MIDI For the Future — Expressive New MIDI Controllers

The Sensel Morph uses many **pressure sensors** to generate continuous MIDI data that can mapped to gestures in musical and non-musical situations.

#### MIDI For the Future — MPE — MIDI Polyphonic Expression

###### MIDI Polyphonic Expression (MPE)

The **continuous pitch** (_glissando_) of these modern controllers  
(_on previous slides_) are made possible thanks to **MPE.**

Normally, **Pitch Bend** messages are sent on _all_ channels at once, but...

MPE allows messages like **Pitch Bend** to be sent for **each individual note**...

#### MIDI For the Future — MPE — MIDI Polyphonic Expression

###### MIDI Polyphonic Expression (MPE)

In other words, MPE gives _each note_ its own pitch bend,  
modulation, pressure, dynamics, and other parameters.

Imagine: _each_ finger or _each_ key acts as its **own MIDI controller**!

#### MIDI For the Future — MPE — MIDI Polyphonic Expression

###### MIDI Polyphonic Expression (MPE)

Like 1982, many instrument builders were trying to address  
problems in their **own way**, without communicating among one another.

Similarly, they needed a **standard language**.

In 2018, MPE was adopted as a standard for polyphonic  
expressiveness by the International MIDI Association.

#### MIDI For the Future — MPE — MIDI Polyphonic Expression

###### MIDI Polyphonic Expression (MPE)

Remember how a single DIN cable can carry 16 MIDI channels?

Traditionally, these were used for 16 different instruments,  
each with its own **Program Change** values.

MPE _repurposes_ the use of MIDI channels: each channel is used  
for a single note, allowing a **polyphony of expressive messaging  
per note** on a single instrument.

The system permits a maximum polyphony of **15 notes**, reserving  
**one master channel** for messages that apply to all notes.

#### MIDI For the Future — MPE — MIDI Polyphonic Expression

###### MIDI Polyphonic Expression (MPE)

A good visualization for how MPE utilizes MIDI messaging

#### MIDI For the Future — MIDI Over USB, TRS, Ethernet, Wireless

###### MIDI Over USB Cables

Today, MIDI devices are frequently connected with faster **USB cables**,  
instead of the older and slower DIN cables.

A single USB cable can act as 16 independent MIDI cables,  
each with 16 channels,  
for a total of 256 MIDI channels.

#### MIDI For the Future — MIDI Over USB, TRS, Ethernet, Wireless

###### MIDI Over TRS Cables

For distances over more than just a few meters,  
a USB or MIDI cable will experience **latency** and **drops in signal**.

A solution has been to use **TRS** cables.  
Like XLR audio cables, TRS can transmit over long distances.

With the growing use of Eurorack analog modular synthesizers,  
which normally use small TS patch cables (close to TRS),  
it is increasingly common to find **MIDI-to-TRS cables**  
connecting controllers to Eurorack modules.

#### MIDI For the Future — MIDI Over USB, TRS, Ethernet, Wireless

###### MIDI Over Ethernet

**Ethernet cables** (used for internet connections)  
are now frequently used to transmit audio.

Now, we also use **ethernet cables** to transmit  
large amounts of MIDI data over large distances,

especially useful when using today's elaborate **MIDI interfaces**,  
which connect many devices in an expansive **network.**

#### MIDI For the Future — MIDI Over USB, TRS, Ethernet, Wireless

###### Wireless MIDI

Today, you can even connect MIDI over wireless networks like **Bluetooth**!

#### MIDI For the Future — Advanced Topics

###### Advanced MIDI Topics

In our other seminars, we frequently discuss these  
and other advanced MIDI issues, like:

*   Human gestural control of MIDI
*   Microtonal resolution of pitch using MIDI
*   Using MIDI values to control custom **samplers** and **microcontrollers**
*   Mapping MIDI values to **control voltage** and other synthesis parameters.
*   Interfacing MIDI control with sensors and **real-world objects**
*   Broadcasting MIDI **over the internet**

#### MIDI For the Future — MIDI Over USB, TRS, Ethernet, Wireless

###### That's the end!

We hope you learned something useful  
to use in your artistic practice!

// More info about initialization & config: // - https://revealjs.com/initialization/ // - https://revealjs.com/config/ Reveal.initialize({ hash: true, progress: true, slideNumber: "c/t", // Learn about plugins: https://revealjs.com/plugins/ plugins: \[ RevealMarkdown, RevealHighlight, RevealNotes \] });