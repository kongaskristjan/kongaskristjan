<h3 align="center">Hi, I'm Kristjan</h3>

<p align="center">
I build tools for peering inside neural networks, tinker with reinforcement learning, and simulate physical systems.
</p>

<!-- ── Project cards ─────────────────────────────────────────── -->
<table align="center">
  <tr>
    <td align="center" valign="top">
      <a href="https://github.com/kongaskristjan/nansense">
        <img src="https://raw.githubusercontent.com/kongaskristjan/nansense/main/assets/docs/max_activations_imagenette.png" height="130" alt="nansense"><br>
        <b>🔬 nansense</b>
      </a><br>
      <sub>See inside your net as it trains</sub>
    </td>
    <td align="center" valign="top">
      <a href="https://github.com/kongaskristjan/stable-entropy">
        <img src="https://raw.githubusercontent.com/kongaskristjan/kongaskristjan/main/assets/stable-entropy-lander.png" height="130" alt="stable-entropy"><br>
        <b>🚀 stable-entropy</b>
      </a><br>
      <sub>Thermodynamics-inspired RL</sub>
    </td>
    <td align="center" valign="top">
      <a href="https://github.com/kongaskristjan/PhaseTransition">
        <img src="https://img.youtube.com/vi/SFf3pcE08NM/maxresdefault.jpg" height="130" alt="PhaseTransition"><br>
        <b>🌡️ PhaseTransition</b>
      </a><br>
      <sub>Real-time particle physics, in your browser</sub>
    </td>
  </tr>
</table>

<!-- ── Details (collapsed by default) ────────────────────────── -->
<details>
<summary><b>🔬 nansense</b> — a PyTorch debugger you can actually see inside</summary>

<br>

Pause your training loop, step batch-by-batch, and **time-travel between epochs** while watching every layer's activations, gradients, weights and optimizer state — live, with nothing written to disk. Run deep dream or Grad-CAM on the paused model to ask what a neuron has really learned.

<p align="center">
  <img src="https://raw.githubusercontent.com/kongaskristjan/nansense/main/assets/docs/ui.png" width="80%" alt="nansense UI on CIFAR"><br>
  <sub><em>The live debugger UI, training on CIFAR.</em></sub>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/kongaskristjan/nansense/main/assets/docs/deep_dream_mnist.png" width="80%" alt="deep dream MNIST"><br>
  <sub><em>MNIST digits deep-dreamed straight out of the output neurons.</em></sub>
</p>

→ <a href="https://github.com/kongaskristjan/nansense">github.com/kongaskristjan/nansense</a>

</details>

<details>
<summary><b>🚀 stable-entropy</b> — thermodynamics-inspired reinforcement learning</summary>

<br>

A reinforcement-learning algorithm (*Policy Annealing*) that nudges high-reward action sequences toward high total probability, much like particles settling into low-energy states. It maps surprisingly cleanly onto ideas such as MaxEnt RL and Path Consistency Learning.

<p align="center">
  <img src="https://raw.githubusercontent.com/kongaskristjan/kongaskristjan/main/assets/stable-entropy-lander.gif" height="200" alt="Lunar Lander agent"><br>
  <sub><em>A trained agent landing in LunarLander (see the repo for CartPole and more).</em></sub>
</p>

→ <a href="https://github.com/kongaskristjan/stable-entropy">github.com/kongaskristjan/stable-entropy</a>

</details>

<details>
<summary><b>🌡️ PhaseTransition</b> — real-time particle simulation (C++ / WebAssembly)</summary>

<br>

A multithreaded particle simulator that reproduces gas ⇄ liquid phase transitions. Create, spray, push and heat particles with the mouse and watch them condense or boil. Builds natively with SDL, or compiles to WebAssembly so it runs right in the browser.

<p align="center">
  <a href="https://youtu.be/SFf3pcE08NM"><img src="https://img.youtube.com/vi/SFf3pcE08NM/maxresdefault.jpg" width="70%" alt="PhaseTransition video"></a>
</p>

▶️ <a href="https://youtu.be/SFf3pcE08NM">Watch the video</a> · 🌐 <a href="https://kongaskristjan.github.io/2020/02/09/phase-transition.html">Try it in your browser</a> · 💻 <a href="https://github.com/kongaskristjan/PhaseTransition">Source</a>

</details>

<details>
<summary><b>🔥 fire-hpp</b> — a C++ command-line interface from a function signature</summary>

<br>

A single-header library that turns a function's parameters into a full CLI. Declare your arguments as `fire::arg` defaults, wrap the function in `FIRE(...)`, and the parsing, type conversion, `--help` text and error messages are handled for you.

```c++
int fired_main(int x = fire::arg("-x"), int y = fire::arg("-y")) {
    std::cout << x + y << std::endl;
    return 0;
}

FIRE(fired_main)
```

→ <a href="https://github.com/kongaskristjan/fire-hpp">github.com/kongaskristjan/fire-hpp</a>

</details>

---

<p align="center">
  <sub>Reach me on <a href="https://www.linkedin.com/in/kristjan-kongas-8030b2254/">LinkedIn</a> or try <a href="https://stackoverflow.com/a/44229207">this</a></sub>
</p>
