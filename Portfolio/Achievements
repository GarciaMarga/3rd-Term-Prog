import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.border.EmptyBorder;
import javax.swing.JButton;
import javax.swing.JLabel;
import javax.swing.ImageIcon;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;

public class Achievements extends JFrame {

	private JPanel Achvmnts;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Achievements frame = new Achievements();
					frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the frame.
	 */
	public Achievements() {
		setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		setBounds(100, 100, 844, 540);
		Achvmnts = new JPanel();
		Achvmnts.setBorder(new EmptyBorder(5, 5, 5, 5));

		setContentPane(Achvmnts);
		setLocationRelativeTo(null);
		Achvmnts.setLayout(null);
		
		JButton btnBack = new JButton("");
		btnBack.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				
				Home Home = new Home();
				Home.setVisible(true);
				dispose();
			}
		});
		btnBack.setIcon(new ImageIcon("C:\\Users\\HP\\Downloads\\7.png"));
		btnBack.setBounds(661, 450, 120, 29);
		Achvmnts.add(btnBack);
		
		JLabel lblNewLabel = new JLabel("");
		lblNewLabel.setIcon(new ImageIcon("C:\\Users\\HP\\Downloads\\8.png"));
		lblNewLabel.setBounds(0, 0, 844, 512);
		Achvmnts.add(lblNewLabel);
		
	}

}
