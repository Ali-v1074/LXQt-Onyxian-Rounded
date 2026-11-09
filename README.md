<img width="1280" height="640" alt="Onyxian-Rounded" src="https://github.com/user-attachments/assets/9f34944b-9f6b-410d-a87b-ec1e1c3c4166" />

# Onyxian-Rounded LXQt Theme

A modern and sleek theme for the LXQt desktop environment.

---

## 🛠️ Installation Instructions

### 1. Install the Theme
Move the `themes` folder to the following path:
`~/.local/share/lxqt/`

### 2. Install the Color Palettes
Move the `palettes` folder to the following path:
`~/.local/share/lxqt/`

### 3. Configure the Panel (Optional Step)
Move the `panel.conf` file to:
`~/.config/lxqt/`

> **Note:** This file is optional; you can keep your own `panel.conf` file settings if you prefer.

#### ⚙️ Custom Panel Setup Guidelines

If you decide not to use the theme's `panel.conf` file and keep your own `panel.conf` file settings, please ensure the following:
* Regardless of the panel position (**top, bottom, left, or right**), ensure the panel size is set to at least **63px**.
* Ensure the panel **icon size is set to either 22px or 24px**, depending on your preference.

If set lower than these values, the panel will appear compressed or squeezed because the theme elevates the panel slightly above the screen edges.

### 4. Enable the Theme
* Open **Appearance** settings.
* From the sidebar menu, select **LXQt Theme**.
* Choose **Onyxian-Rounded** from the list.

**Additional Recommended Adjustments:**
* **Task Manager:** After adjusting the panel size, it is recommended to modify the Task Manager settings to **Width: 47px or 49px**, depending on your preference, and **Height: 45px**. Also, set the display option to **Only icon** instead of **Icon and text**.
* **Status Notifier:** It is recommended to hide icons you don't need in the Status Notifier to save panel space and keep the panel looking clean and uncluttered.

---

## 📋 Requirements

* **Kvantum Engine:** Required for widget styling (buttons, menus, etc.).

* **Kvantum Theme:** Choose [Orchis-solid kvantum (OpenDesktop)](https://store.kde.org/p/1458909/), [Orchis-solid kvantum (GitHub)](https://github.com/vinceliuice/Orchis-kde).

  > **Note:** If you do not want to use the recommended theme, make sure to configure the following settings in **Kvantum Manager**:
  > * Set **Layout spacing** and **Layout margin** to **3px** or **4px**.
  > * Set **Minimum scrollbar length** to **60px**.
  > * It is recommended to set **Tooltip delay** to **1000 ms** or **1500 ms**.
  > 
  > <details>
  > <summary>View Kvantum Settings Screenshot</summary>
  > 
  > <img width="912" height="935" alt="Kvantum-Manager" src="https://github.com/user-attachments/assets/6c706aec-d77c-4b87-9a24-385c60834529" />
  > 
  > </details>

* **Font:** Make sure **Noto Sans** is selected in the LXQt Appearance settings (`lxqt-config-appearance`).

* **Wallpaper:** A solid black wallpaper is required to ensure the panel border is clearly visible. You can use the default wallpaper bundled with the theme.

---

## 📸 Screenshots

<details>
<summary>LXQt Panel</summary>

<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/57adf78b-6246-4184-9fb3-5dbc03fad3d3" />

</details>

<details>
<summary>Wing Menu</summary>

<img width="764" height="812" alt="2" src="https://github.com/user-attachments/assets/3177c49e-5901-4d5c-9533-06c7114ba501" />

</details>

<details>
<summary>LXQt Runner</summary>

<img width="532" height="478" alt="3" src="https://github.com/user-attachments/assets/976a4de4-873e-4f54-be88-cca8357b643d" />

</details>

<details>
<summary>Plugins</summary>

<img width="390" height="562" alt="image" src="https://github.com/user-attachments/assets/b5637a63-4ced-4b04-b9b9-24314c8311de" />

</details>

<details>
<summary>LXQt Notifications</summary>

<img width="359" height="329" alt="5" src="https://github.com/user-attachments/assets/08a6e4c1-9696-4c1b-ae38-01a13662e273" />

</details>

<details>
<summary>LXQt Leave</summary>

<img width="679" height="610" alt="6" src="https://github.com/user-attachments/assets/5d8c01a5-2590-4888-9c04-2b6fe0cf498f" />

</details>
