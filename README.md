start kali 
// import java.util.Timer;
// import java.util.TimerTask;
// import javax.swing.*;
// import java.awt.*;
// import java.text.SimpleDateFormat;
// import java.util.Date;

// public class DigitalClock extends JFrame {
//     private JLabel clockLabel;

//     public DigitalClock() {
//         clockLabel = new JLabel();
//         clockLabel.setFont(new Font("Arial", Font.PLAIN, 48));
//         clockLabel.setHorizontalAlignment(SwingConstants.CENTER);
//         add(clockLabel);
//         setSize(400, 200);
//         setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
//         setVisible(true);

//         Timer timer = new Timer();
//         timer.schedule(new TimerTask() {
//             @Override
//             public void run() {
//                 updateClock();
//             }
//         }, 0, 1000);
//     }

//     private void updateClock() {
//         String currentTime = new SimpleDateFormat("HH:mm:ss").format(new Date());
//         clockLabel.setText(currentTime);
//     }

//     public static void main(String[] args) {
//         new DigitalClock();
//     }
// }


