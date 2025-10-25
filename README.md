# Personal History Timeline - User Guide


## Getting Started

Personal History Timeline comes with sample data to help you learn how to use the features. You can modify or delete any sample records as you explore. If you want to restore the sample data later, you can:

- Export your current data using "Export Records"
- Re-import the saved data anytime using "Import Records"

## Main Interface Overview

The application window is organized into several helpful sections:

### Control Panels at the Top

The main interface has five control panels across the top:

1. **Timeline Navigation**: Choose which year to view and navigate through time
2. **Event Actions**: Add, Edit, and Delete your personal events
3. **Search and Data Tools**: Find and manage your information
4. **Import/Export**: Move data into and out of the application
5. **Appearance**: Customize colors and themes

### Timeline View

A visual timeline showing your events arranged in chronological order. Events appear as markers with dates and connecting lines.

### Events List

A detailed table showing all events for the currently selected year with columns for:

- **Date**: When the event occurred
- **Event**: What happened
- **Category**: How to classify the event
- **Tags**: Keywords for people, places, or things
- **Detail**: Additional information about the event

### Status Bar

Shows current information about your data and any operation results.

## Working with Events

### Adding New Events

1. **Click "Add Event"** in the Event Actions panel
2. **Fill in the Event Form**:
   - **Date**: Use the calendar button to choose the date (Required)
   - **Event**: Write a brief description of what happened (Required)
   - **Category**: Choose how to classify this event (Family, Work, Personal, etc.)
   - **Tags**: Add keywords separated by commas (people, places, things)
   - **Detail**: Write additional information if needed
3. **Click "OK"** to save your event

### Editing Existing Events

1. **Click on an event** in the Events List table
2. **Click "Edit Event"** to open the editing form
3. **Make your changes** in the form
4. **Click "OK"** to save your changes

### Deleting Events

1. **Click on an event** in the Events List table
2. **Click "Delete Event"**
3. **Confirm deletion** when asked

### Organizing Your Events

**Categories** help you group similar events:

- Family (births, weddings, anniversaries)
- Work (jobs, promotions, achievements)
- Personal (education, hobbies, health)
- Travel (trips, vacations, moves)

**Tags** let you add flexible keywords:

- Use multiple tags separated by commas
- Examples: "Jim, Marie, Paris" or "Birthday, Family, Celebration"

## Timeline Visualization

### Understanding Your Timeline

The timeline shows events in chronological order for the year you've selected:

- **Timeline Line**: The main horizontal line representing time
- **Event Markers**: Circles showing individual events
- **Event Labels**: Date labels above markers
- **Connecting Lines**: Vertical lines for events on the same date

### Using the Timeline

- **Click markers** to select events
- **Hover over markers** to see event details in popup windows
- **Selected events** are highlighted with a colored outline

### Timeline Features

- **Automatic Organization**: Events on the same date are stacked vertically
- **Smart Labeling**: Labels are positioned to avoid overlapping
- **Easy Scrolling**: Timeline can be scrolled to see all information
- **Synchronized Selection**: Selecting events in the timeline highlights them in the Events List

## Search and Filter

### Year Navigation

Use the year selector to view events from different years:

1. **Click "Pick Year"** to open the year selection popup
2. **Click "â† Previous Year"** to go backward in time
3. **Click "Next Year â†’"** to go forward in time

### Comprehensive Search

Click "Comprehensive Search" to open the advanced search dialog with four equal-width sections:

#### 1. Search Text
- **Search for**: Enter any word to find in your events
- **Search in**: Choose which fields to search (All Fields, Event, Category, Tags, Detail)

#### 2. Use Date Range
- **Checkbox**: Check "Use date range" to enable date filtering
- **From**: Enter start date (YYYY-MM-DD format) or use calendar button ðŸ“…
- **To**: Enter end date (YYYY-MM-DD format) or use calendar button ðŸ“…

#### 3. Filters
- **Category**: Choose from dropdown of existing categories
- **Tags**: Choose from dropdown of existing tags

#### 4. Search Controls
- **Search**: Apply your criteria and show matching events
- **Show All**: Display all records in your database
- **Clear Table**: Empty the results table

### Search Results

The search dialog shows results in a table with these buttons:

- **Select All**: Select all events in the results
- **Clear Selection**: Deselect all events
- **Export Selected...**: Export only selected events
- **Export All...**: Export all events in the results
- **Batch Processing**: Edit multiple events at once (appears when events are selected)

### Batch Processing

Edit multiple events at the same time:

1. **Use Comprehensive Search** to find the events you want to edit
2. **Select events** in the search results (use Ctrl+click for multiple rows)
3. **Click "Batch Processing"** to open the batch processing dialog
4. **Choose which fields to update** by checking the boxes:
   - **Update Date**: Check to change dates, enter new date
   - **Update Event**: Check to change event descriptions, enter new text
   - **Update Category**: Check to change categories, enter new category
   - **Update Tags**: Check to change tags, enter new tags
   - **Update Detail**: Check to change details, enter new detail text
5. **Preview changes** in the preview table showing old vs. new data
6. **Click "Apply Changes"** to update all selected events

### Bulk Data Entry

Create recurring annual events (Birthdays, Anniversaries, School Years) quickly:

1. **Click "Bulk Data Entry"** on the main page
2. **Fill in the Event Details** (left side):
   - **Base Event**: The first occurrence (e.g., "Birth", "Wedding", "New Chevy")
   - **Annual Event**: Pattern for subsequent years (e.g., "Jimmy is", "Anniversary")
   - **Tag**: Common tag for all event-years (e.g., "Family", "Personal")
   - **Detail**: Common description for all event-years (optional)
3. **Set the Date Range** (right side):
   - **Start Date**: When to begin creating events
   - **End Date**: When to stop creating events
   - Use calendar buttons ðŸ“… for easy date selection
4. **Preview the results** in the table below
5. **Click "Create Events"** to add them all to your database

### Remove Duplicates

Find and remove duplicate events from your entire database:

1. **Click "Remove Duplicates"** on the main page
2. The system will scan your entire database for duplicates
3. **Review the duplicates** found (if any)
4. **Select which duplicates to remove** by checking the boxes
5. **Click "Remove Selected"** to clean your database

## Import and Export

### Importing Data

Import events from spreadsheet files:

1. **Click "Import Records"** in the Import/Export panel
2. **Select your spreadsheet file** (previously created with a spreadsheet program)
3. **Review the import preview** to see what will be imported
4. **Confirm import** to add events to your timeline

#### File Format Requirements

Your spreadsheet file must include these columns:

- **date**: Event date (YYYY-MM-DD format preferred)
- **event**: Event description

Optional columns:

- **category**: Event category
- **tags**: Comma-separated tags
- **detail**: Extended description

### Exporting Data

Export your timeline data:

1. **Click "Export Records"** in the Import/Export panel
2. **Choose export scope**:
   - All events
   - Current view (events currently displayed)
   - Single year
   - Year range
3. **Select export location**
4. **Click "Export"** to create a file with a timestamp

### Backup and Restore

**Create Backups**:

1. **Click "Backup Records"** in the Import/Export panel
2. Records will be saved to your Home directory unless you choose otherwise
3. **Backup file** is created with timestamp
4. **Note:** You have an opportunity to delete all database records after a backup

**Restore from Backup**:

1. Use the **Import Records** feature to perform restore functions
2. **Select a recent backup file**
3. **Import events** back into the timeline
4. Note: This may introduce duplicates into your database, so be careful

## Customization

### Themes

Choose between Light and Dark themes:

1. **Click "Light"** for traditional light background with dark text
2. **Click "Dark"** for modern dark background with light text

### Accent Colors

Customize the application's accent color:

1. **Click "Accent Color"** in the Appearance panel
2. **Choose a color** from the color picker
3. **Color is applied** immediately to highlights and accents

### Column Widths

Adjust table column widths:

- **Drag column borders** in the Events List to resize
- **Settings are saved** automatically
- **Detail column** always stretches to fill available space

## Data Management

### Where Your Data is Stored

Your timeline data is stored in a hidden folder on your computer:

- **Database file**: Contains all your events
- **Log file**: Records application activity
- **Settings**: Stores your preferences

### Data Safety

**Automatic Features**:

- Data is saved immediately when you make changes
- Database includes integrity checks
- Connection management prevents data corruption

**Manual Backups**:

- Use "Backup Records" regularly
- Keep backups in safe locations
- Test restore procedures periodically

## Tips and Best Practices

### Event Organization

1. **Use consistent categories**: Establish a standard set of categories
2. **Tag effectively**: Use descriptive, searchable tags
3. **Be specific in descriptions**: Include context and details
4. **Use dates consistently**: Stick to standard date formats

### Data Entry Efficiency

1. **Bulk Data Entry**: Use for recurring events like birthdays, anniversaries
2. **Copy and modify**: Edit similar events rather than starting from scratch
3. **Import large datasets**: Use spreadsheet .csv import for historical data
4. **Regular backups**: Backup your data weekly or monthly

### Search Strategies

1. **Start broad**: Use general terms, then narrow with filters
2. **Use categories and tags**: To filter your search into smaller result sets
3. **Date ranges**: Limit searches to specific time periods

### Timeline Navigation

1. **Use year filter**: Focus on one year at a time
2. **Scroll efficiently**: Use Previous/Next buttons for timeline navigation
3. **Select events**: Click timeline markers for quick selection

### Getting Help

**Built-in Help**:

- Use "User Guide" button for this documentation
- Check "About" for version and contact information

**Support Resources**:

- Email: parsemonkey@gmail.com
- Include application version and error details
- Describe steps to reproduce issues
