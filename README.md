# Advanced Report Composer — User Guide & Features

## 1. Introduction
The **Advanced Report Composer** is a modern, interactive, and user-friendly tool designed to simplify report creation directly in the browser. It allows users to load, manipulate, and export data in multiple formats with an intuitive drag-and-drop interface. This solution eliminates the need for complex backend reporting setups, making it perfect for business analysts, managers, and developers who want fast, actionable reporting.

---

## 2. Current Features

### 2.1 Upload JSON / Excel (XLSX) Files
- Users can upload either JSON or Excel (.xlsx) files.
- Automatically parses data and displays it in the Source Table.
- Supports large datasets with pagination for improved performance.
- Provides error handling for unsupported formats.

### 2.2 Search & Filter Source Data
- A search bar allows filtering rows in real-time.
- Supports keyword search across all columns.
- Enables quick access to relevant data without scrolling through large datasets.

### 2.3 Paginated Source Table
- Supports pagination for large datasets.
- Default 20 rows per page (configurable).
- Navigation buttons allow switching between pages: Prev / Next.
- Provides current page indicators for clarity.

### 2.4 Drag & Drop to Target Report
- Drag rows from source to target table using **SortableJS**.
- Reorder rows directly in the target report.
- Remove actions for individual rows.
- Full control over the composition of the final report.

### 2.5 Live Report Preview
- Displays the current state of the target report.
- Automatically updates whenever data is added, removed, or reordered.
- Helps visualize the final output before exporting.

### 2.6 Excel Export
- Export the target report to Excel (.xlsx) with a single click.
- Includes all data in the target table.
- Maintains structured headers matching the source table.

### 2.7 JSON Export
- Export the target report as JSON, preserving the original data structure.
- Useful for backend integration, API usage, or sharing with other systems.

### 2.8 PDF Export
- Export the target report as a formatted PDF.
- Uses **html2pdf.js** for precise layout and A4 page formatting.
- Preserves table structure, headers, and styling.

### 2.9 Print
- Direct printing of the target report.
- Utilizes the live preview panel for WYSIWYG printing.
- Supports default browser print settings for cross-device compatibility.

### 2.10 Clear Target
- Single button clears all rows in the target report.
- Resets the Live Preview automatically.
- Quickly start over without refreshing the page.

---

## 3. Advantages
- **No Backend Dependency:** Fully client-side processing, works in the browser without server scripts.
- **Ease of Use:** Intuitive drag-and-drop interface with immediate live preview.
- **Cross-Platform Compatibility:** Works on desktops, laptops, and tablets with responsive layout.
- **Multiple Export Options:** Excel, JSON, PDF, and Print.
- **Dynamic & Interactive:** Live updates, pagination, and search/filter capabilities.
- **Scalable:** Handles thousands of rows efficiently with pagination.

---

## 4. Upcoming Features (Planned Enhancements)
- **Save to Database:** Save target reports directly to the database; column type selection and auto-create table structures.
- **Custom Column Calculations:** Add formula-based columns like SUM, AVG.
- **Conditional Formatting:** Highlight rows or cells based on thresholds.
- **Multiple Table Merging:** Combine multiple source tables into a single target report.
- **Advanced Pagination & Filtering:** Multi-column sort and export of selected pages.
- **User Permissions & Roles:** Role-based access for viewing, exporting, and editing reports.

---

## 5. User Interface Overview
- **Header Toolbar:** Upload, Excel Export, JSON Export, PDF Export, Print, Clear Target.
- **Source Panel:** Search bar, paginated table with drag handles.
- **Target Panel:** Dragged rows, live preview section for PDF/Print.
- **Modal Preview:** Shows live report output.

---

## 6. Technology Stack
- **Frontend:** HTML, CSS, JavaScript
- **Libraries:**
  - **SortableJS:** Drag & drop
  - **html2pdf.js:** PDF generation
  - **SheetJS (XLSX):** Excel parsing and export
  - **Fonts & Icons:** Inter Font, RemixIcon

---

## 7. Conclusion
The Advanced Report Composer provides a robust, client-side solution for creating professional reports quickly and efficiently. With drag-and-drop functionality, live preview, multiple export formats, and flexible data handling, it reduces reliance on traditional reporting tools and speeds up data-driven decision-making.

Future versions will include database integration, conditional formatting, and advanced analytics, making it a complete end-to-end reporting solution for businesses.

---
