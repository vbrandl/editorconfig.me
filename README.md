# Editorconfig.me

[![Build Status](https://travis-ci.org/vbrandl/editorconfig.me.svg?branch=master)](https://travis-ci.org/vbrandl/editorconfig.me)
[![codecov.io](http://codecov.io/github/vbrandl/editorconfig.me/coverage.svg?branch=master)](http://codecov.io/github/vbrandl/editorconfig.me?branch=master)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/vbrandl/editorconfig.me/blob/master/LICENSE)

Inspired by [gitignore.io](https://gitignore.io) I thought it would be a good idea to have a similar web service for a collection of [EditorConfig](http://editorconfig.org/) settings.

Editorconfig.me aims to fulfill the target by offering a HTTP API to request a EditorConfig file for a given list of languages.

Currently it is just a web API implemented in Rust using [hyper](https://github.com/hyperium/hyper) and [reroute](https://github.com/gsquire/reroute). Currently there is no graphical Frontend to view in the browser but it is planed.


