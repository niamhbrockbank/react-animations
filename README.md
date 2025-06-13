# React animations

This repo started with a fully functioning React app where _challenges_ can be tracked. My input was adding animations to it in line with the Udemy course "React - The Complete Guide 2025".

## Installation
* Run `npm install` to install dependencies on setup
* Run `npm run dev` to start the development server

## Technologies used
* CSS transitions and animations
* [Motion](https://motion.dev/) animations
    * animate
    * transition
    * initial - used for entry animations
    * exit - used for exit animations
    * whileHover
    * variants - reusing animation states and passing animations to children components
    * staggering animations with `staggerChildren` in transition and `stagger()` when animating imperatively
    * `useAnimate`
    * `useScroll` and `useTransform` for scroll based animations
    * the `layout` prop for taking advantage of Motion's in-built layout animations
    * utilising `layoutId` for shared element animations