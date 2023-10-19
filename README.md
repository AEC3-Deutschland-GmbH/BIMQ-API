# BIMQ: API

Welcome to the [BIMQ](https://bimq.de) API documentation.

## Getting Started

### Endpoints

You can find the full documentation
on [Postman (external site)](https://documenter.getpostman.com/view/17439674/UVJkAsuk).

### Changelog and Example Responses

Demo response files for every available request are available as `JSON` files.

#### v1

[Examples](examples/v1)

- 2023-08-31
    - Translations are added for Purposes, Phases and Actors.
    - Phase and Purpose code for purposes are added.
- 2023-10-18 (BIMQ 2.9 and higher)
    - `get_concept_tree`:
        - information for `actor` (`code`, `name`, `id`) are added to concepts of type `geometry` and `property`
        - example JSON file fixed (fields were missing for all concepts: `code`, `unit`, `unit_reference`)

## Contributing and Contact

Do you have questions, feature requests or discovered any error?
Please feel free to open an [Issue](https://github.com/AEC3-Deutschland-GmbH/BIMQ-API/issues)
or contact us via [support@bimq.de](mailto:support@bimq.de?subject=API).
