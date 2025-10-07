# householdbudget.github.io

import javafx.scene.control.Label;
import javafx.scene.layout.VBox;
import javafx.scene.text.Font;
import javafx.scene.text.FontWeight;
public class Slide5 {
    public VBox getContent() {
        VBox vbox = new VBox(15);
        vbox.setPadding(new Insets(20));
        Label title = new Label("Slide 5: Feature Implementation Deep Dive");
        title.setFont(Font.font("Arial", FontWeight.BOLD, 24));
        Label gamificationTitle = new Label("Gamification & Rewards:");
        gamificationTitle.setFont(Font.font("Arial", FontWeight.BOLD, 16));
        Label gamificationDesc = new Label("Points and badges awarded on key actions (saving targets, regular logging)");
        Label calendarTitle = new Label("Calendar Integration:");
        calendarTitle.setFont(Font.font("Arial", FontWeight.BOLD, 16));
        Label calendarDesc = new Label("OAuth2-based sync with Google/Outlook; Create/update events for due dates");
        Label bankTitle = new Label("Bank API Integration:");
        bankTitle.setFont(Font.font("Arial", FontWeight.BOLD, 16));
        Label bankDesc = new Label("Secure Plaid API, encrypted tokens, recurring transaction auto-detection");
        Label savingsTitle = new Label("Savings Goal Tracker:");
        savingsTitle.setFont(Font.font("Arial", FontWeight.BOLD, 16));
        Label savingsDesc = new Label("Dynamic progress bars, daily backend computation
