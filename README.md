This repository contains a simple transformer implementation in pytorch, made to be both (reasonably) fast and still readable.<br/>
Note that this will <b>always</b> slower than the native pytorch version: It for example contains flash attention (tl;dr: optimisation to make attention computation much faster).<br/>
The inner workings, however, are the same.
