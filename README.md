# AutoAdX demo photos

Illustrative photos of the fictional cars in the AutoAdX demo tenant
(`demo-pack/seed/stock.json` in the AutoAdX repository).

**Every photo is AI-generated** by an image model, from a description of each
car's make, model, generation and colour (`demo-pack/seed/generate-photos.py`).
No real car, number plate, dealer or person is pictured: plates are blank and
there is no branding beyond the car maker's own badge. Each photo was checked
by eye against the generation recorded for its car.

Files are named `<stock number>_<view>.jpg`. Every car has a `front` view; the
six cars given car videos in the demo also have `rear`, `side`, `head` and
`rear2`.

The repository is public only so that the demo's video worker, which reads
photos from a public web address, can fetch them.
