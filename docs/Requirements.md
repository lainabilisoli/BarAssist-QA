# Requirements Specification

## Purpose

This document defines the functional requirements for BarAssist and serves as the basis for test planning, test case design, test execution, and requirements traceability.

## Application Overview

BarAssist is a mobile cocktail recipe application designed for everyone from beginners to professional bartenders. The application enables users to quickly search for cocktail recipes using voice or text input, making it especially useful in busy bartending environments where hands-free access is valuable.

## Functional Areas

#### Functional Requirements

**FR-001.001**  
The application shall display the BarAssist splash animation when launched.

**FR-001.002**  
The splash animation shall display the BarAssist branding before completing.

**FR-001.003**  
On first launch, the application shall navigate to the onboarding experience after the splash animation.

**FR-001.004**  
On subsequent launches, the application shall navigate directly to the listening screen after the splash animation.

---

#### Functional Requirements

**FR-002.001**  
The application shall display the onboarding experience on first launch.

**FR-002.002**  
The user shall be able to navigate through the onboarding slides.

**FR-002.003**  
Completing or skipping onboarding shall navigate the user to the listening screen.

**FR-002.004**  
The application shall remember that onboarding has been completed and shall not display it again unless reset.

---

#### Functional Requirements

**FR-003.001**  
The application shall request microphone permission when required.

**FR-003.002**  
The application shall begin listening for spoken drink orders after microphone permission has been granted.

**FR-003.003**  
The application shall identify supported cocktail names from spoken voice input.

**FR-003.004**  
The application shall navigate directly to the corresponding recipe when a supported cocktail is identified.

**FR-003.005**  
The application shall notify the user when no matching cocktail recipe is found.

**FR-003.006**  
The application shall support consecutive voice recognition sessions without restarting the application.

---

#### Functional Requirements

**FR-004.001**  
The application shall display the selected cocktail recipe.

**FR-004.002**  
The application shall allow users to navigate through previously recognized recipes within the current session.

**FR-004.003**  
The application shall provide a Lock control that temporarily suspends voice recognition.

**FR-004.004**  
The application shall allow users to resume voice recognition after unlocking.

**FR-004.005**  
Closing the application shall clear the current recipe navigation history.

---

### FA-005 Manual Recipe Search

#### Functional Requirements

FR-005.001
The application shall allow users to search for cocktail recipes by entering the name of a cocktail.

FR-005.002
The application shall display the corresponding recipe when a matching cocktail is found.

FR-005.003
The application shall notify the user when no matching cocktail recipe is found.

---

### FA-006 Account Management

**Screens:**
- Account

**Description:**
Allows users to view their remaining free recipe searches, manage their subscription, and customize application preferences.

#### Functional Requirements

**FR-006.001**  
The application shall display the user's remaining free recipe searches.

**FR-006.002**  
The application shall provide access to the Premium screen.

**FR-006.003**  
The application shall allow users to switch between Light Mode and Dark Mode.

**FR-006.004**  
The application shall remember the user's selected theme between application sessions.
---

### FA-007 Premium

**Screens:**
- Premium

**Description:**
Allows users to upgrade to BarAssist Premium for unlimited recipe navigation.

#### Functional Requirements

**FR-007.001**  
The application shall display the benefits of BarAssist Premium.

**FR-007.002**  
The application shall allow users to initiate a Premium purchase.

**FR-007.003**  
The application shall unlock unlimited recipe navigation after a successful Premium purchase.

**FR-007.004**  
The application shall retain Premium access across future application sessions.

---

### FA-008 Help & Instructions

**Screens:**
- Instructions

**Description:**
Provides users with information on how to use the application.

#### Functional Requirements

**FR-008.001**  
The application shall provide instructions on how to use BarAssist.

**FR-008.002**  
The application shall explain the application's primary features.

**FR-008.003**  
The user shall be able to navigate back to the previous screen from the Instructions page.

---

### FA-009 Contact & Support

**Screens:**
- Contact & Support

**Description:**
Provides users with a simple way to contact the BarAssist team.

#### Functional Requirements

**FR-009.001**  
The application shall display the BarAssist support email address.

**FR-009.002**  
The application shall open the user's default email application when the support email address is selected.

**FR-009.003**  
The user shall be able to navigate back to the previous screen.

---

### FA-010 Navigation Drawer

**Screens:**
- Listening Screen
- Recipe Screen

**Description:**
Provides users with quick access to the application's primary screens from anywhere within the main application workflow.

#### Functional Requirements

**FR-010.001**  
The application shall provide access to the Navigation Drawer from both the Listening screen and the Recipe screen.

**FR-010.002**  
The application shall display navigation options for Manual Search, Instructions, Account, Premium, and Contact & Support.

**FR-010.003**  
The application shall navigate to the selected screen when a navigation option is selected.

**FR-010.004**  
The user shall be able to close the Navigation Drawer without selecting a navigation option.

**FR-010.005**  
The application shall preserve the current application state when opening and closing the Navigation Drawer.
