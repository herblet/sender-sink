[![Crates.io](https://img.shields.io/crates/v/sender-sink.svg)](https://crates.io/crates/sender-sink)
![CI](https://github.com/herblet/sender-sink/actions/workflows/build_with_coverage.yml/badge.svg)
[![codecov](https://codecov.io/gh/herblet/sender-sink/branch/main/graph/badge.svg?token=2DKFJT5UZJ)](https://codecov.io/gh/herblet/sender-sink)

A tiny crate which provides a `futures::sink::Sink`-implementing wrapper around `tokio::sync::mpsc::UnboundedSender`.
