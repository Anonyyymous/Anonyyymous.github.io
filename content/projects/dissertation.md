+++
title = "Dissertation"
description = "A networking and physics engine for simple 2D games in Rust"
[extra]
status = "In Progress"
languages = "Rust"
technologies = ""
# image_url = "images/cs276.png"
# image_alt = "cs276-image-alt"
# link = "https://github.com/Anonyyymous/cs276-game-dev"
+++
For networking, this uses meta-programming to compile a function tagged as an
RPC into 3 distinct parts and a serializable payload - the wrapper (which
converts the input args into the payload struct and serializes it, deserializes
the response - executed on the sender), the receiver (which receives the input
from the runtime as bytes, and deserializes it back into a payload to be sent to
the core - executed on the receiver), and the core (which is just the code from
the original function).

Rust is quite a nice choice for this, with its lovely meta-programming out of
the box, as well as derivable traits that mean I can just tell the compiler that
the payloads will derive the `Serializable`/`Deserializable` traits, and it will
error if they cannot.

My end goal for the project includes:

- RPC function tags (including variables like delivery importance)
- A derivable trait that automagically updates selected fields each physics
frame via the runtime
- Subscribable events
- A network-compatible rigidbody physics engine (though the networking runtime/trait)
should be able to be used by itself

I am intentionally avoiding using AI for this, since I wish to release this as
an open source project at the end. If I find part of it too cumbersome to reason
about or use, then it should be changed, not brute forced by an agent.
Furthermore, I am deeply interested in the fields involved, and wish to learn as
much about them as possible.

Oh, and also uni regulations I guess.
