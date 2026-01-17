gsap.timeline()
  .to(".brand-name", { duration: 1, opacity: 1, y: -20, ease: "power2.out" })
  .to(".swoosh", { duration: 0.8, scaleX: 1, ease: "power2.out" }, "-=0.5")
  .to(".subtext", { duration: 1, opacity: 1, y: 10, ease: "power2.out" }, "-=0.4");

