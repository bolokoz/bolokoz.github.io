---
title: Install Jupyter
layout: post
date: 2017-1-19
description: Using Docker
image: 'http://lorempixel.com/400/200/'
category: python
published: true
---


# What is Jupyter and Docker

This probably is not very accurate but **for me** Jupyter is a python framework that lets you write a notebook and occasionally can use programming to display results and calculations in a pretty way. Which it makes perfect for a lot of cases, mostly reproducible research and tutorials.

Docker ships the complete package so you won't hear 'it works in my machine' ever again.

## First install Python

- Linux: You probably already have installed Python.
- Windows: just google Python, it's very easy. I recommend installing version 3 instead of version 2.

## Install Docker

- Linux: >sudo apt-get install docker-engine
- Windows: go to docker website and figure it out Lol

## Install Jupyter

Now just type
>docker run -it --rm -p 8888:8888 jupyter/tensorflow-notebook
