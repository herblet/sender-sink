[![Crates.io](https://img.shields.io/crates/v/tokio-sink.svg)](https://crates.io/crates/tokio-sink)
![CI](https://github.com/herblet/tokio-sink/actions/workflows/build_with_coverage.yml/badge.svg)
[![codecov](https://codecov.io/gh/herblet/tokio-sink/branch/main/graph/badge.svg?token=2DKFJT5UZJ)](https://codecov.io/gh/herblet/tokio-sink)

A tiny crate which provides a `futures::sink::Sink`-implementing wrapper around `tokio::sync::mpsc::UnboundedSender`.
