# Mosaic-project-ps1
CAPTCHAs (Completely Automated Public Turing
Tests to Tell Computers and Humans Apart) are
something that almost every internet user has
encountered. Many users are presented with
strange-looking, stretched, fuzzy, coloured, and shape
distorted visuals that look more like a Dali painting
than English text while signing in or creating an
account, making an online purchase, or even
publishing a comment.

With the growth of Artificial Intelligence, Machine
Learning and Computer Vision, the need for strong
captchas has increased, so that Computer Vision
models are unable to automatically detect these
captchas.

This year’s Problem Statement for round 1 is based
exactly on this. Handwritten Captcha Detection. Your
task is to automatically detect what is written in the
Captcha given to you. Generally simple captchas
consist of numbers and letters in a distorted format,
but there is a twist to the PS. Instead of numbers, the
captcha will consist of letters and emojis (from a
predefined set - the link to which is given in the
resources).
The captcha will consist of handwritten letters and
emojis written with black ink on a white paper.
There’ll be bonus points for additional features, such
as handling distorted and rotated images, or removing
noise in the captcha before detection.

You have to map the emojis in the captcha to numbers,
i.e. when you print the output, you need to print the
number corresponding to the emoji detected in the
captcha,
The mapping will be as follows:
Checkmark : 1
Cloud: 2
Croissant: 3
Heart: 4
Laugh: 5
Smile: 6
Sun: 7
