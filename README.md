# trane-n-back

Improve working memory with Trane and N-back exercises.

# N-back

N-back is a working memory exercise that consists of remembering the position of a stimulus in a
series of stimuli. For a meta-analysis of the claims of N-back exercises, see this
[FAQ](https://gwern.net/dnb-faq).

# Instructions

- Install Brain Workshop from [http://brainworkshop.net/](http://brainworkshop.net/).
- Install Trane using the instructions from the [quick start
guide](https://trane-project.github.io/quick_start.html)
- Install this course by running the command  `repository add
  https://github.com/trane-project/trane-n-back.git` inside trane.
- Open the trane library again to reload the contents.

# Course structure

The course starts you on the easiest type of exercise (single 1-back mode with 5 seconds per trial),
and gradually increases the difficulty as you progress.

A few examples of how exercises are written are presented below:

- "Practice single 2-back mode with 3 seconds per trial."
- "Practice dual 4-back mode with 5 seconds per trial."

The first thing it mentions is the type of exercise, which can be:

- Single: Only position
- Dual: Position and sound.
- Triple: Position, sound, and color.
- Quad: Position, sound, color, and shape.

The second thing it mentions is the n-back mode, which can range from one to twelve, although the
upper limit is lower for dual, triple, and quad modes.

The third thing it mentions is the time per trial, which is either 5, 3, or 2 seconds. You start by
practicing with 5 seconds per trial, and then you can move to 3 seconds per trial, and finally to 2.

The number of trials is up to the user, but I usually go for 20 trials per exercise.

To work with exercise type, you need to select the specified mode in Brain Workshop by selecting it
in the manual mode options. See the [documentation](http://brainworkshop.net/details.html) for more
info.
