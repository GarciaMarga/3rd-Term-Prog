import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.border.EmptyBorder;
import javax.swing.JButton;
import javax.swing.JLabel;
import javax.swing.ImageIcon;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;

public class Home extends JFrame {

	private JPanel Home;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Home frame = new Home();
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
	public Home() {
		setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		setBounds(100, 100, 844, 540);
		Home = new JPanel();
		Home.setBorder(new EmptyBorder(5, 5, 5, 5));

		setContentPane(Home);
		setLocationRelativeTo(null);
		Home.setLayout(null);
		
		//About Me
		JButton btnAbtme = new JButton("");
		btnAbtme.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				
				AboutMe abtMe = new AboutMe();
				abtMe.setVisible(true);
				dispose();
			}
		});
		btnAbtme.setIcon(new ImageIcon("C:\\Users\\HP\\Downloads\\4.png"));
		btnAbtme.setBounds(109, 406, 184, 56);
		Home.add(btnAbtme);
		
		//Skills and Abilities
		JButton btnsklls = new JButton("");
		btnsklls.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				
				SkillsAndAbilities Sklls = new SkillsAndAbilities();
				Sklls.setVisible(true);
				dispose();
			}
		});
		btnsklls.setIcon(new ImageIcon("C:\\Users\\HP\\Downloads\\5.png"));
		btnsklls.setBounds(327, 406, 184, 56);
		Home.add(btnsklls);
		
		//Achievements
		JButton btnAchvmnts = new JButton("");
		btnAchvmnts.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				
				Achievements Achvmnts = new Achievements();
				Achvmnts.setVisible(true);
				dispose();
			}
		});
		btnAchvmnts.setIcon(new ImageIcon("C:\\Users\\HP\\Downloads\\6.png"));
		btnAchvmnts.setBounds(556, 406, 184, 56);
		Home.add(btnAchvmnts);
		
		JLabel homeBG = new JLabel("");
		homeBG.setIcon(new ImageIcon("C:\\Users\\HP\\Downloads\\1.png"));
		homeBG.setBounds(0, 0, 844, 512);
		Home.add(homeBG);
		
	}
}
