

## Effect of the P, I, D component of the PID algorithm.

- P component controlled the steering angle, higher the P coefficient,
greater the steering angle.
- D component controlled and smoothed the oscillation effect caused by the P
coefficient.
- use of I component was not necessary.

Values of P,I,D were manually tuned to get a smoother convergence to
vehicle trajectory, starting with higher Kp, and lower Kd, and gradually reducing Kp, and gradually increasng Kd until reaching desired performance.

following P,I,D coefficient values were used:

    Kp = -0.1
    Ki = 0.0
    Kd = -2.0


here is the output:

<img src="pid-control.gif" video>
