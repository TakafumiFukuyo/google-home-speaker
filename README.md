[![Build Status](https://travis-ci.org/freddiefujiwara/google-home-speaker.svg?branch=master)](https://travis-ci.org/freddiefujiwara/google-home-speaker)
[![Build status](https://ci.appveyor.com/api/projects/status/f6wch68buqp93hc7/branch/master?svg=true)](https://ci.appveyor.com/project/freddiefujiwara/google-home-speaker/branch/master)
[![CircleCI](https://circleci.com/gh/freddiefujiwara/google-home-speaker.svg?style=svg)](https://circleci.com/gh/freddiefujiwara/google-home-speaker)
[![npm version](https://badge.fury.io/js/google-home-speaker.svg)](https://badge.fury.io/js/google-home-speaker)
[![codecov](https://codecov.io/gh/freddiefujiwara/google-home-speaker/branch/master/graph/badge.svg)](https://codecov.io/gh/freddiefujiwara/google-home-speaker)
[![dependencies Status](https://david-dm.org/freddiefujiwara/google-home-speaker/status.svg)](https://david-dm.org/freddiefujiwara/google-home-speaker)

# google-home-speaker
Command line client for chromeless

## Requirements

 - Node 7.6 or later

## Installation

```bash
npm i -g google-home-speaker
```

## Usage
```bash                                                                                     
  Usage: google-home-speaker [options] [source.cmd]                                                                                    
                                                                                                                               
  Command line client for chromeless                                                                                             
                                                                                                                               
                                                                                                                               
  Options:                                                                                                                     
                                                                                                                               
    -V, --version     output the version number
    -h, --help        output usage information  
```

## Example
```bash
goto http://www.google.com
type google-home-speaker 'input[name="q"]'
click 'input[type="submit"]'
wait #resultStats
screenshot
```

## FAQ

[FAQ](https://github.com/freddiefujiwara/google-home-speaker/wiki/FAQ)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/freddiefujiwara/google-home-speaker