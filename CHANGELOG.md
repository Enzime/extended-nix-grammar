# Change Log

All notable changes to the "nix-ext" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

- Added unescaped and escaped string interpolation examples
- Added expression after multiline string examples
- Fixed injection grammar breaking when encountering escaped multiline string delimiters
- Extended Nix grammar to support language annotations in block comments before a multiline string
- Fixed `TODO` and other text inside block comments not getting highlighted
- Added `nix.tmLanguage.json` from `nix-ide`
- Added injection grammar to extend Nix multiline strings to support language annotations
